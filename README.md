# Noughts and Crosses (Tic Tac Toe) Game

This is a simple web-based noughts and crosses (tic-tac-toe) game built using React. The primary focus of this exercise was to demonstrate parent-child communication and React building structures.

## How to Play

1. The game starts with Player O.
2. Players take turns clicking on squares to place their symbol (O or X).
3. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
4. If all squares are filled and no player has three in a row, the game ends in a draw.

## Features

- Dynamic updating of the game board based on player moves.
- Interactive interface allowing players to click on squares to make their moves.
- Real-time feedback on the current player's turn.
- Instant detection of the winner or draw.

## How to Run Locally

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Open your web browser and navigate to `http://localhost:3000` to play the game.

## Components

- **Board**: Manages the game state and renders the grid of squares. Tracks the current player's turn and updates the game state accordingly.
- **Square**: Represents each individual square on the game board. Receives click events from players and notifies the parent (Board) when a square is filled.
- **Game**: Parent component that wraps the entire game. Simply renders the Board component.

## Built With

- React: A JavaScript library for building user interfaces.
- JavaScript: The primary programming language used for logic and interactivity.
- HTML/CSS: For structuring and styling the game interface.

## Demo

<a href= "https://sean-mongey.github.io/Nought-and-Crosses/">Click here to play</a>

## Roadmap

- Block players from choosing squares that have already been selected. 
- Add a reset button.
- Prevent players from making moves after the game has finished.
- Add a score board to track previous games.


## License

MIT License

## Acknowledgements

Special thanks to Dr. Williams for providing the initial code and exercise inspiration.
