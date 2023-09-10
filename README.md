# Etch-A-Sketch
# Grid Drawing Web App

The Grid Drawing Web App is a simple web application that allows users to create and save grids of customizable sizes. Users can draw on the grid using a black or white pen (eraser mode), save their drawings, and access previously saved grids.

## Features

- **Grid Creation:** Users can create a new grid by specifying the number of squares per side (up to 100) using the "New Grid" button.

- **Drawing:** Users can draw on the grid by clicking and dragging the mouse over the cells. They can switch between drawing and erasing modes using the "Eraser" button.

- **Grid Saving:** Users can save their current grid by clicking the "Save Grid" button. Saved grids are stored in the browser's local storage.

- **Access Saved Grids:** Users can access previously saved grids by clicking on the links displayed under the "Old Grids" section.

## Usage

1. **Creating a New Grid:**
   - Click the "New Grid" button.
   - Enter the desired number of squares per side (up to 100) in the prompt.
   - A new blank grid of the specified size will be created.

2. **Drawing and Erasing:**
   - Click and drag the mouse over the grid cells to draw (in black by default).
   - To switch to eraser mode, click the "Eraser" button. In eraser mode, drawing will be in white.

3. **Saving a Grid:**
   - Click the "Save Grid" button to save the current grid state.
   - The saved grid will be added to the list of old grids.

4. **Accessing Saved Grids:**
   - Under the "Old Grids" section, click on the links labeled "Grid 1," "Grid 2," and so on to access previously saved grids.

## Development

This web app is built using HTML, CSS, and JavaScript. Here's an overview of the main files and their functions:

- `index.html`: The main HTML file that defines the structure of the web app and includes the JavaScript code.

- `style.css`: The CSS file that provides styling for the web app elements, including buttons, grid cells, and links.

- `script` (within `index.html`): The JavaScript code that handles grid creation, drawing, saving, and loading of grids from local storage.


## Acknowledgments

This web app was created as a simple drawing tool and learning exercise. It may be enhanced and extended in the future with additional features and improvements.