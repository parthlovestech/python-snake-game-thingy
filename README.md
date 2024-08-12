# Snake Game

This is a simple implementation of the classic Snake Game using Python's Pygame library.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/parthlovestech/python-snake-game-thingy.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd python-snake-game-thingy
   ```

3. **Install the required dependencies:**
   Make sure you have Python installed. Then, install Pygame using pip:
   ```bash
   pip install pygame
   ```

4. **Run the game:**
   ```bash
   python snake_game.py
   ```

## How to Play

- Use the arrow keys on your keyboard to move the snake.
- The objective is to eat the food (white square) to grow the snake.
- The game ends when the snake runs into the walls or into its own body.
- Your score is displayed at the top left corner.

### Controls:
- **Arrow Keys**: Control the direction of the snake
- **C Key**: Play Again after losing
- **Q Key**: Quit the game

## Game Features

- **Score Display:** The score is displayed at the top left corner.
- **Snake Movement:** The snake can be controlled using arrow keys.
- **Game Over:** The game ends if the snake runs into the screen border or itself.
- **Restart Option:** The player can choose to restart or quit after losing.

## Code Structure

- **gameLoop()**: The main function that runs the game loop.
- **score_display(score)**: Displays the current score on the screen.
- **draw_snake(snake_block, snake_list)**: Draws the snake on the screen.
- **message(msg, color)**: Displays a message on the screen (used for game over message).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can modify the sections and add more information based on your preferences before uploading to GitHub.
