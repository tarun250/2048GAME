2048 Game Project

Overview

This project is a browser-based implementation of the popular 2048 game. It is built using HTML, CSS, and JavaScript. The game provides an interactive grid where players can combine numbered tiles to achieve the coveted 2048 tile. It supports both arrow keys and WASD keys for movement.

Features

Dynamic Grid: A 4x4 grid where tiles dynamically update based on user input.

Responsive Design: The game board adjusts seamlessly for various screen sizes.

Keyboard Controls: Supports movement using arrow keys (Up, Down, Left, Right) and WASD keys.

Merge Logic: Automatically merges tiles with the same number when moved.

Random Tile Generation: Adds a new tile (2 or 4) in a random empty position after each valid move.

Game Over Detection: Alerts the user when no moves are left.

Tile Styling: Distinct colors for tiles based on their values.

How It Works

File Structure

HTML: Provides the structure of the game grid.

CSS: Styles the grid, tiles, and overall appearance.

JavaScript: Implements game logic, tile generation, and user interaction.

Code Highlights

1. Grid Initialization

The grid is represented as a 2D array initialized with zeros:
