# mandelbulb

This repository contains a Processing sketch for generating and visualizing a Mandelbulb fractal in 3D. The Mandelbulb is a 3D fractal, an extension of the Mandelbrot set into three dimensions.

## Description

This sketch uses the Processing and PeasyCam libraries to generate and display the Mandelbulb. The algorithm iterates over a 3D grid of points, applying a fractal formula to determine whether each point belongs to the Mandelbulb set. Points on the boundary of the set are then plotted in 3D space.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/mandelbulb-visualization.git

2. **Open the project in Processing:**
   Ensure you have the Processing IDE installed.
   Open mandelbulb.pde in the Processing IDE.

3. **Install the PeasyCam library:**

Go to Sketch -> Import Library -> Add Library...
Search for PeasyCam and install it. 

## Usage
Run the mandelbulb.pde sketch in the Processing IDE. (https://processing.org/download) 
You can interact with the visualization using the mouse to rotate and zoom in/out.

## Code Explanation
setup(): Initializes the canvas and camera, and generates the Mandelbulb points.
draw(): Renders the Mandelbulb points in 3D space.
spherical(): Converts Cartesian coordinates to spherical coordinates for the fractal calculation.
Mandelbulb Generation: Iterates over a 3D grid, applying the fractal formula to determine boundary points.

## Example
<img width="597" alt="mandelbulb" src="https://github.com/trolex213/mandelbulb/assets/65372052/ffec2014-edb5-4fa1-aafb-0a969221d2e9">

## License
This project is licensed under the MIT License - see the LICENSE file for details.
   
