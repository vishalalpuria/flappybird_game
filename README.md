## Flappy Bird Game in Python

This is a recreation of the classic Flappy Bird game built with Pygame. Help the bird avoid pipes and score points by flying through the gaps!

**Features:**

* Animated bird flapping
* Scrolling pipes (top and bottom)
* Point scoring system
* Collision detection with pipes and ground
* Game Over screen

**How to Play:**

1. Clone or download this repository.
2. Install the `pygame` library using `pip install pygame`.
3. Run the script using `python main.py` (replace `main.py` with the actual script name if different).
4. Press space or the up arrow key to make the bird flap and fly.
5. Avoid hitting the pipes or the ground.

**Code Structure:**

* The code is divided into several functions:
    * `welcomeScreen`: Displays the welcome message and waits for the user to start the game.
    * `mainGame`: Handles the main game loop, including bird movement, pipe generation, collision detection, and scoring.
    * `isCollide`: Checks for collision between the bird and pipes or ground.
    * `getRandomPipe`: Generates random positions for the top and bottom pipes.
    * Functions to load and display game sprites (bird, pipes, background, numbers) and sounds.

**Further Improvements:**

* Implement difficulty levels with increasing pipe speed.
* Add visual effects for bird flapping, scoring, and game over.
* Create a menu system for options and sound control.

**Feel free to explore and modify this code as you see fit!**

**Note:**

* This game uses image and sound assets located in the `gallery/sprites` and `gallery/audio` folders (not included in this repository due to file size). You'll need to replace the placeholder image paths with your own or find these assets online.

I hope this README provides a clear overview of the Flappy Bird game project!