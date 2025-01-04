# masai-project
Tic Tac Toe Game

This repository contains a simple implementation of the classic Tic Tac Toe game in Python. The game allows a human player to compete against the computer.

Project Description

This Tic Tac Toe project provides an interactive way to play the game in the terminal. It supports a single human player against the computer, with basic AI logic implemented for the computer's moves. The game board is displayed in the terminal, and the player inputs their moves by selecting a position (1-9).

Features Implemented

Interactive terminal-based gameplay.

Supports human vs. computer gameplay.

Automatic detection of winning conditions:

Horizontal rows

Vertical columns

Diagonals

Tie detection when no moves are left.

Dynamic switching between players (X and O).

Basic AI for the computer's moves.

How to Run the Project

Ensure you have Python installed on your system (Python 3.6 or later).

Clone this repository to your local machine.

git clone https://github.com/your-username/tic-tac-toe.git

Navigate to the project directory.

cd tic-tac-toe

Run the script using Python.

python tic_tac_toe.py

Follow the on-screen instructions to play the game.

Instructions for Installation

This project does not require any external libraries to run. Ensure Python is installed and available in your terminal. If you do not have Python installed, download it from the official Python website.

Gameplay Instructions

Start the game:

The game board will be displayed as a 3x3 grid, initially filled with - to indicate empty spots.

Make your move:

The player playing as X will be prompted to select a spot on the board by entering a number (1-9) corresponding to the position.

Computer's turn:

The computer (O) will randomly select an empty spot on the board.

Win, lose, or tie:

The game will announce a winner when three of the same symbols align horizontally, vertically, or diagonally.

If all spots are filled without a winner, the game declares a tie.

Restart:

To play again, simply rerun the script.

Example Output

- | - | -
---------
- | - | -
---------
- | - | -
Select a spot 1-9: 5
- | - | -
---------
- | X | -
---------
- | - | -
The computer chooses a spot.
...
The winner is X!

Contributions

Feel free to fork this repository, submit issues, or create pull requests to improve the project.

License

This project is open source and available under the MIT License.

