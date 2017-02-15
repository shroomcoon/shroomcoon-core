# shroomcoon-core

## Features

* Main loop
  * requestAnimationFrame only (screw browser compatibility)
* Event emitter
  * on(), emit(), once()...
  * Game events
    * update
    * tick
* Game state
  * Running/Paused...

Following could be in renderer module?

* Game object pool
* Game.draw()

Takes a canvas, or a parent element to place a canvas in, in which case the canvas is created.
