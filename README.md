# Geocentric Solar System

An animation of the solar system seen from the Earth, drawn on an HTML canvas.

The Earth stays fixed at the center of the screen. The Moon and the Sun orbit around it, and the planets orbit around the Sun. As each body leaves a fading trail, the animation reveals the loops (retrograde motions) that the planets seem to trace in the sky when observed from the Earth.

## Usage

No installation or build step is needed: open `index.html` in a web browser.

## Files

- `index.html`: the page that loads the script and the stylesheet.
- `main.js`: the `Planet` class and the animation loop.
- `style.css`: the page style.

## Settings

The following variables at the top of `main.js` control the animation:

- `globalScale`: overall scale factor.
- `speedScale`: speed of the orbital motion.
- `distanceScale`: scale of the orbital distances (in astronomical units).
- `radiusScale`: scale of the body sizes.
- `maxFrame`: number of frames before the animation stops (`-1` for no limit).

Orbital distances and periods (in days) are approximately the real ones; body sizes are not to scale.
