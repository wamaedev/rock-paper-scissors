# Rock Paper Scissors Game

A simple browser-based Rock Paper Scissors game where you play against the computer for 5 rounds. The game is played through the console with prompts for user input.

## How to Play

1. Open the `index.html` file in your web browser
2. The game will automatically start and prompt you to enter your choice
3. Play 5 rounds against the computer
4. Results are displayed in the browser's console

## Game Rules

- Rock beats Scissors
- Paper beats Rock
- Scissors beats Paper
- Same choices result in a tie

## Files

- `index.html` - The main HTML file that loads the game
- `script.js` - Contains all the game logic

## How It Works

The game consists of several functions:

- `getComputerChoice()` - Randomly generates the computer's move (rock, paper, or scissors)
- `getHumanChoice()` - Prompts the player for their choice and validates input
- `playRound()` - Compares choices and determines the winner of each round
- `playGame()` - Manages 5 rounds of gameplay and announces the final winner

## Playing the Game

When you open the HTML file, the game immediately starts in the console. You'll see prompts asking for your choice. After 5 rounds, the final winner is announced in the console.

To view results:
- Open browser's Developer Tools (F12 or Right-click → Inspect)
- Navigate to the Console tab
- Follow the prompts and watch the results appear

## Example Gameplay
Prompt: "Please enter: Rock, Paper, or Scissors"
User enters: "rock"
Console: "You win! Rock beats Scissors!"

... (4 more rounds)

Console: "You win!" (if you won more rounds than the computer)

## Future Improvements

Potential enhancements could include:
- Adding a graphical user interface with buttons
- Displaying scores on the page instead of console
- Adding animations for choices
- Keeping track of game history

## Technologies Used

- HTML5
- JavaScript (ES6+)

## Author

Created as a simple JavaScript project to practice functions, conditionals, and game logic.