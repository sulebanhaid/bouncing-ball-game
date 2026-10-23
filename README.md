# Interactive Bouncing Ball Physics Simulation

## Overview
This is an interactive physics simulation written in C using raylib.
Users can add and remove balls, pause the simulation, change gravity and bounce energy, and reset the simulation. Balls collide with the window edges and with each other.
## Controls
- Left-click: add a ball
- Right-click: remove a ball
- Space: pause or resume
- C: clear all balls
- R: reset the simulation
- Up/Down arrows: change gravity
- Left/Right arrows: change bounce energy

## Project Structure
- `main.c`: main loop, input and interface
- `ball.c`: ball movement, drawing and collision behaviour
- `ball.h`: ball structure and public function declarations

## Compilation
```bash
gcc main.c ball.c -o game -lraylib -lopengl32 -lgdi32 -lwinmm
