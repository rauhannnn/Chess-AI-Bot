# Chess AI Bot

This repository contains a Chess AI Bot I built using Python and TensorFlow, where the AI plays chess against the user by evaluating board positions and making strategic moves. The bot uses a neural network to process the chessboard, extracting key features to predict the best possible move at each step.

## Project Overview

This project involves building a chess-playing AI bot that:
- Interacts with a user in real-time by prompting them for moves.
- Uses a **neural network** built with **TensorFlow** to evaluate and generate the bot’s moves based on the current board configuration.
- Displays the chessboard and updates it after every move, visually representing the game progress.

### Key Features of the Neural Network:

1. **Neural Network with Convolutions**:
   - The bot’s neural network uses **convolutional layers** to process the chessboard as a grid (8x8) and extract important features such as piece positions, attacks, defenses, and positional advantages.
   - These features allow the bot to make informed decisions by recognizing patterns on the board and responding with optimal moves.
   
2. **Move Prediction**:
   - The model predicts the best possible move by analyzing the board state and outputting a move that improves the bot's position, taking into account both offensive and defensive strategies.

## Project Details

- **Language**: Python
- **Libraries Used**:
  - `python-chess`: For representing the chessboard and handling game logic.
  - `tensorflow`: To build and train the neural network responsible for move prediction.
  - `numpy` and `pandas`: For data manipulation and preprocessing.

- **Neural Network**:
  - **Convolutions** are used to extract spatial features from the 8x8 chessboard grid, allowing the network to evaluate piece positioning and potential strategies.
  - **Fully connected layers** use the extracted features to predict the best move for the bot based on the current board state.
