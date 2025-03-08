# Memory Game

## Overview

The Memory Game is a simple browser-based game where players flip cards to find matching pairs. The game is built using HTML, CSS, and JavaScript.

## Project Structure

```
MemoryGame/
├── index.html
├── styles.css
├── script.js
├── README.md
```

## Requirements

- A modern web browser (Chrome, Firefox, Safari, etc.)

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MemoryGame.git
   cd MemoryGame
   ```

2. Open the `index.html` file in your web browser to start the game.

## Gameplay

- The game consists of a grid of cards, each with a hidden character.
- Click on a card to flip it and reveal the character.
- Click on a second card to try to find a matching pair.
- If the cards match, they remain flipped and are marked as matched.
- If the cards do not match, they are flipped back after a short delay.
- The game continues until all pairs are matched.

## Code Explanation

### HTML (index.html)

The HTML file contains the basic structure of the web page, including a heading and a container for the game cards.

### CSS (styles.css)

The CSS file styles the game elements, including the body, heading, game container, and cards. It also includes styles for the flipped and matched states of the cards.

### JavaScript (script.js)

The JavaScript file contains the logic for the memory game:

- **shuffle(array)**: Shuffles the cards array to ensure a random order each time the game is played.
- **createCard(character)**: Creates a card element and adds an event listener for flipping the card.
- **flipCard()**: Handles the card flip action, checks for matches, and manages the game state.
- **checkForMatch()**: Checks if the two flipped cards match and either disables them or unflips them.
- **disableCards()**: Disables the event listener for matched cards and adds a matched class.
- **unflipCards()**: Unflips the cards after a short delay if they do not match.
- **resetBoard()**: Resets the board state after each turn.
- **initGame()**: Initializes the game by shuffling the cards and creating the card elements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Your Name - [your.email@example.com](mailto:ingleshreyas01@gmail.com)
