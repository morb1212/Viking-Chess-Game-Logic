# viking-chess Game Logic

This Java project provides a flexible and extensible framework for implementing the logic of a chess-like board game. It offers essential functionality for managing players, pieces, and game rules.

## Overview

The project consists of several key components:

- **GameLogic**: Implements the core logic for controlling the game flow, managing player turns, and determining game outcomes.
- **Piece**: Defines the behavior and attributes of individual game pieces.
- **Player**: Represents the players participating in the game.

## Features

- **Modular Design**: The project is designed with modularity in mind, allowing for easy extension and customization of game rules and piece behavior.
- **Player Management**: Supports multiple players, each with their own set of pieces and game statistics.
- **Flexible Piece Behavior**: Pieces can be easily customized to implement various movement patterns, capture rules, and special abilities.
- **Game State Management**: Provides functionality for saving and restoring game state, enabling features like undo/redo and game replays.
- **Extensive Documentation**: The codebase is thoroughly documented to facilitate understanding and modification.

## Usage

To use this project in your own Java application:

1. **Integrate the Code**: Copy the necessary classes (`GameLogic`, `Piece`, `Player`, etc.) into your project directory.
   
2. **Customize Piece Behavior (Optional)**: Modify the `Piece` class or create subclasses to define custom movement and capture rules for different types of pieces.
   
3. **Initialize Game Logic**: Instantiate the `GameLogic` class to initialize the game and start playing.
   
4. **Implement UI (Optional)**: Create a user interface to interact with the game, allowing players to make moves, view game state, and access game controls.
   
5. **Extend Functionality (Optional)**: Extend the project to add additional features such as AI opponents, multiplayer support, or advanced game analysis tools.

## Tests

### GameLogic Test

- **Objective**: Ensure that the core game logic functions correctly.
- **Steps**:
  1. Set up a game with predefined pieces and players.
  2. Execute various game actions such as moving pieces, capturing opponents' pieces, and checking for victory conditions.
  3. Verify that the game state is consistent with the expected outcomes after each action.

### Piece Behavior Test

- **Objective**: Validate the behavior of individual game pieces.
- **Steps**:
  1. Test the movement patterns of each type of piece, including normal movement, capturing opponent pieces, and special moves (if any).
  2. Confirm that pieces behave according to the rules defined for their type and that illegal moves are not allowed.

