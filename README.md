Handy Bird
=========

Play Flappy Bird by actually flapping your hands.

[<img src="https://media.giphy.com/media/UHbpTnnoxbG9O/giphy.gif">](https://wanderingstan.github.io/handybird/)

Play it now here: https://wanderingstan.github.io/handybird/

Notes
---
* Does _not_ work in Firefox. Works well in Chrome.
* Sound must be on and maximized. You may hear the high-pitched tone it uses. Best to use built-in laptop speaker.
* Microphone access must be allowed. It listens to the change in the tone to detect motion.
* Flap your hand toward your microphone. On Macbook it is by top-left of the keyboard. You may have to Google where it is on your computer.
* The speaker or microphone on some computers may not be able to handle the 20kHz tone used for the doppler detection.

History
---
I was totally amazed by [Daniel Rapp's demo](https://github.com/DanielRapp/doppler) that its possible to detect hand movement using the doppler effect in javascript. Given that I must make everything into a game, Flappy Bird was the obvious choice.
Nebez Briefkani had already created a great javascript version, [Floppy Bird](https://github.com/nebez/floppybird). Excellent code in both projects enabled this mash-up.

Local Development
---
To develop on a local machine, you'll have to start a webserver. This should work:

    python -m SimpleHTTPServer 8000

The microphone is not permitted on local html pages.
