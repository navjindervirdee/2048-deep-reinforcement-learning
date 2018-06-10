# Trained A Neural Network To Play 2048 using Deep-Reinforcement Learning

## Watch the Network Playing 2048!

<p align = "center">
<img src =  https://github.com/navjindervirdee/2048-deep-reinforcement-learning/blob/master/Game%20Video/game.gif >
</p>

## 2048 Game
2048 is a single-player sliding block puzzle game designed by Italian web developer Gabriele Cirulli. The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048; however, you can keep playing the game, creating tiles with larger numbers.

2048 is played on a gray 4×4 grid, with numbered tiles that slide smoothly when a player moves them using the four arrow keys.Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move. Higher-scoring tiles emit a soft glow.

A scoreboard on the upper-right keeps track of the user's score. The user's score starts at zero, and is incremented whenever two tiles combine, by the value of the new tile. As with many arcade games, the user's best score is shown alongside the current score.

The game is won when a tile with a value of 2048 appears on the board, hence the name of the game. After reaching the 2048 tile, players can continue to play (beyond the 2048 tile) to reach higher scores. When the player has no legal moves (there are no empty spaces and no adjacent tiles with the same value), the game ends.

## Reinforcement Learning
Reinforcement learning (RL) is an area of machine learning inspired by behaviourist psychology, concerned with how software agents ought to take actions in an environment so as to maximize some notion of cumulative reward. The problem, due to its generality, is studied in many other disciplines, such as game theory, control theory, operations research, information theory, simulation-based optimization, multi-agent systems, swarm intelligence, statistics and genetic algorithms. In the operations research and control literature, reinforcement learning is called approximate dynamic programming, or neuro-dynamic programming. The problems of interest in reinforcement learning have also been studied in the theory of optimal control, which is concerned mostly with the existence and characterization of optimal solutions, and algorithms for their exact computation, and less with learning or approximation, particularly in the absence of a mathematical model of the environment. In economics and game theory, reinforcement learning may be used to explain how equilibrium may arise under bounded rationality.

## Network Architecture
![](https://github.com/navjindervirdee/2048-deep-reinforcement-learning/blob/master/Architecture/Architecture.JPG?raw=true)

## Activation Function and Optimizer 
* Activation - RELU
* Optimizer  - RMSPRop

## Deep Learning Framework
* Tensorflow

## Loss Graph
* Y-AXIS = Avg Loss of 50 games
* X-AXIS = Number of Episodes

<p align = "center">
<img src = https://github.com/navjindervirdee/2048-deep-reinforcement-learning/blob/master/Loss/Loss.png?raw=true>
</p>

## Scores Graph
* **Max Tile Reached = 4096**
* **MAX Score Reached = 59724**

* Y-AXIS = Avg Score of the 50 games
* X-AXIS = Number of Episodes

<p align = "center">
<img src = https://github.com/navjindervirdee/2048-deep-reinforcement-learning/blob/master/Score/Score.png?raw=true>
</p>

## Game Outcome:

<p align = "center">
<img src = "https://github.com/navjindervirdee/2048-deep-reinforcement-learning/blob/master/Game%20Outcomes/Outcome.JPG?raw=true">
</p>
