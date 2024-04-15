## Flask Application Design

### HTML Files
- **index.html**: The main HTML file for the game, featuring:
  - A 30-second countdown timer.
  - An 8 by 4 grid of cells, each with an initial color of white.
  - Event listeners for cell clicks to change cell colors.

### Routes
- **index**: The main route that renders the index.html file.
- **countdown**: A route that handles the countdown timer and resets the grid cells to white when the timer reaches 0.
- **cell_color**: A route that changes the color of a selected cell to green, purple, or yellow based on the player's choice.