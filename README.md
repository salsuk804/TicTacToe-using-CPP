# TicTacToe-using-CPP


# Tic Tac Toe Game 

This is a simple console-based Tic Tac Toe game implemented in C++. Two players alternate turns entering box numbers (0-8) to place their markers. The game checks for winning conditions (rows, columns, and diagonals) and declares the winner or a draw with a random winner.

## Features
- Two-player Tic Tac Toe gameplay in the console.
- Input validation to prevent duplicate and out-of-range entries.
- Checks for winning conditions after all moves.
- In case of a draw, only one random player is declared winner as per game rules.

## Restrictions
- The code does **not** use functions; it is implemented entirely in the `main` function.
- No use of classes or advanced C++ features.
- Input box numbers must be between 0 and 8 inclusive.
- The program expects valid integer inputs; entering non-integer input may cause runtime errors.
- The game does not display the current board state graphically during play.
