# Guess-The-Number
 This project is a fun and interactive number guessing game built with HTML, CSS, and JavaScript. The game generates a random number between 1 and 100, and players have up to 10 attempts to guess it correctly.
# Features
* Random Number Generation: A random number between 1 and 100 is generated each time the game starts.
* Input Validation: Ensures players enter a valid number within the specified range, providing helpful prompts for incorrect inputs.
* Feedback System: Guides players by displaying if their guess is too high, too low, or correct.
* Game Over Functionality: Ends the game after 10 guesses or when the correct number is guessed, displaying the hidden number if not guessed correctly.
* Play Again Option: Allows players to start a new game with a new random number after each round.
# Code Overview
* validateGuess(): Checks the player’s input to ensure it is a valid number within the range of 1 to 100.
* checkGuess(): Compares the player’s guess with the randomly generated number and displays feedback.
* displayGuess(): Keeps track of and displays the player’s previous guesses, updating the remaining attempts.
* endGame(): Disables further input after the game ends and displays a "Start New Game" button.
* newGame(): Resets the game state and generates a new random number when the "Start New Game" button is clicked.
