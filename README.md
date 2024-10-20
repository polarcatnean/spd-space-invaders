# Space Invaders

This project is a simple design/mockup of the classic arcade game **Space Invaders**, developed as a final project for the **How to Code: Simple Data** course.

## Overview

The game features a basic version of Space Invaders where:
- The player controls a **tank** that can move left and right at the bottom of the screen using the arrow keys.
- The **tank** can shoot **missiles** upwards by pressing the space bar.
- **Invaders** appear randomly at the top of the screen and move diagonally, bouncing off the walls.
- The game ends when an invader reaches the bottom of the screen.


## Setup and Running the Game

### Prerequisites
- This game is developed in **Racket** and should be run using **DrRacket**.

### How to Run
1. Open the provided `.rkt` file in **DrRacket**.
2. Click **Run** to execute the program.
3. After all tests pass, start the game by calling the function `main` in the **Interactions** window with the initial game state: 
   ```racket
   (main G0)
   ```

## Configuration

You can adjust the speed of the invaders, tank, and the spawn rate of the invaders in the **Constants** section of the code.

### Constants:

- **`INVADER-SPEED`**: Adjusts the speed of the invaders. Higher values mean faster invader movement.
- **`TANK-SPEED`**: Adjusts the speed of the tank. Higher values mean faster tank movement.
- **`SPAWN-RATE`**: Controls how frequently new invaders spawn. A higher value means invaders spawn faster.

You can modify these constants as follows:

```racket
(define INVADER-SPEED 5)   ; Adjust invader speed
(define TANK-SPEED 3)      ; Adjust tank speed
(define SPAWN-RATE 100)    ; Adjust invader spawn rate
```

Increasing these numbers will increase the speed or spawn rate, making the game more challenging.
   
