# Nim.ai
Welcome to the Nim.ai where an artificial intelligence, named Nimma, trains itself through reinforcement learning, by playing against itself repeatedly and learning from experience, eventually the system will learn which actions to take and which actions to avoid. 

For those who don't know about Nim, the game begins with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.

Nimma uses the Q-Learning algorithm to create reward system for the reinforcement learning process. An action that loses the game will have a reward of -1, an action that results in the other player losing the game will have a reward of 1, and an action that results in the game continuing has an immediate reward of 0, but will also have some future reward. 

With these rules in mind, Nimma goes through a training period of 10,000 games where it keeps playing the game with itself and rewards and punishes itself, given a situation 

