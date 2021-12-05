# maze-runner.AI
An AI powered 2-d grid  based game 

Maze-Runner is actually a maze through which the human player (named Mariko) has to run through and collect the coins simultaneously. 
Our game is having several modifications to any available 2-d grid AI  game. Enemy bots are configured to attack and kill human players. Our game has 5 different enemy bots (named “RED”,” Blue”,” Yellow”,” Pink”, and  “Black”). Our game is based upon a point system. It is a one-person game, if the player gobbles up a designated number of coins in the game, then the player wins. Our enemy bots will be competing from head to head with their different AI engines to kill the player. When the game is in player mode, a win condition is given to the highest-scoring human player, regardless of the AI effect. Additionally, our game state will contain “Magic Pellets” which will offer players special powers such as attack capability, invincibility, wall smashing…etc. 
Software/Game Engine:
The software side of our project is coded in Python.
Pygame libraries have been used for developing game graphics.
 The game engine will store the information of the game map along with the states of the player and enemy units. The game engine is divided into the following major components. 
Game State: 
The game state is represented by the grid[][] data structure, it is essentially a 1200X800 two-dimensional integer array.
Playing State: It is a working game with moving enemy bots and human players.

