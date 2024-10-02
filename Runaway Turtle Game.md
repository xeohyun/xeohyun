# Runaway Turtle Game

This is a simple turtle graphics-based game where the player (the "runner") must avoid multiple chasers while collecting points represented by fish. The game speeds up as time progresses, and the goal is to survive for as long as possible while collecting points.

## How to Play

- **Player Control**: 
  - Use the arrow keys (`Up`, `Down`, `Left`, `Right`) to move the player, represented by a green turtle, across the screen.
  
- **Objective**: 
  - Collect the fish that appear randomly on the screen to increase your score.
  - Avoid the red chasers that attempt to catch you. The game ends if any chaser catches you.
  
- **Chasers**: 
  - The game starts with 3 red chasers. New chasers are added every 5 seconds, increasing the difficulty over time.
  - Chasers get faster as time progresses.

- **Points**: 
  - Every time you collect a fish (represented by a small fish icon), your score increases by 1 point.
  - After collecting a point, the fish reappears at a new random location on the screen.

- **End of the Game**:
  - The game ends when a chaser catches the player. Your final score is calculated as the number of points collected and the time you survived.

## Game Features

- The game has no time limit, allowing players to try and survive as long as possible.
- The speed of the chasers increases over time, making the game more challenging the longer you play.
- The player's score is based on both the survival time and the points collected.