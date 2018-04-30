# Minesweeper game in the Command license

## Setup
- Clone the repo
- run `npm install`
- run `npm build` to transpile from ES6 (a folder named **lib** will be created)

## How to play
- `cd` into the lib folder
- run `node`
- run `.load game.js` to load the contents of this file
- Then create a Game instance and run commands like so: `let game = new Game(3, 3, 3);`
- play move: `game.playMove(0, 1);`
- When done run `.exit`
