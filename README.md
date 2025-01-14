# Udemy_Course

### 1.Deep Q-Learning for Lunar Landing

This code implements the Deep Q-Learning algorithm to solve the Lunar Lander problem in OpenAI Gym. The objective is to train an agent to land a spacecraft safely between the flags.

A neural network is utilized as a function approximator for estimating Q-values. The agent stores experiences from previous interactions with the environment in a replay memory, enabling it to learn from past actions and outcomes. The Q-values are updated iteratively using the Bellman equation to optimize the agent's decision-making.

The training process focuses on enabling the agent to develop policies for stable and successful landings. Finally, the performance of the trained agent is visualized, showcasing its ability to land effectively and safely within the designated area.

### 2.Deep Q-Learning for Pac Man

This code is also similar to the deep Q-learning code of lunar landing, but in this code it is for Pac Man.This code is implemented using the gymnisium module, where there is state space and the action space,
first pre-processing is done so that the frames are suitable for the neural network model and then Q-value is estimated and then after cycle the Q-value is update using the bellman equation.


The agent interacts with the Pac-Man game over multiple episodes, aiming to learn optimal actions for maximizing the score. After each move, it stores experiences in a replay buffer and uses them to train the neural network, improving its decision-making capabilities. 

### 3.A3C for Kung Fu

