# Game of Life

This is a simple implementation of Conway's Game of Life using HTML, CSS, and JavaScript. The Game of Life is a cellular automaton devised by the mathematician John Conway in 1970. It is a zero-player game that simulates the evolution of a population of cells on a two-dimensional grid.

## How to Play

1. Open the HTML file in a web browser.
2. The game starts automatically.
3. Click anywhere on the canvas to begin the simulation.
4. Cells will evolve and change color according to the rules of the Game of Life.
5. Enjoy the mesmerizing patterns that emerge!

## Features

- Randomly initializes the cells on the grid.
- Implements the rules of the Game of Life to determine cell evolution.
- Displays the grid using HTML canvas.
- Changes the color of cells to create an aesthetically pleasing visualization.
- Plays background music during the simulation.
- Supports looped playback of the background music.

## Controls

- **Click**: Starts the simulation and plays background music.

## Customization

- You can modify the size of the canvas by changing the `width` and `height` attributes of the `<canvas>` element.
- The speed of the simulation can be adjusted by changing the value passed to `setInterval` in the `updateGame` function.
- The colors used for the cells can be customized by modifying the `neonColors` array in the `getRandomNeonColor` function.

Note: Ensure that the audio file `audio.mp3` is present in the same directory as the HTML file, or update the `music.src` attribute with the correct file path.

## Compatibility

This code should work on modern web browsers that support HTML5 canvas and audio features.

## Credits

This implementation was created by PC and is based on the Game of Life devised by John Conway.

Have fun exploring the fascinating world of the Game of Life!
