# Q Learning
This repository contains implementation of Q learning algorithms used in various Reinforcement Learning Tasks.

Deep Q learning agent was built to play Pong environment provided **OpenAI Gym** in **Pytorch**

This takes frames of images as the only input. So it must learn to distinguish between different elements of the game. 

As itself Deep Q Learning takes large time to converge. To improve on this following techniques were used
1. Experience Replay
2. Fixed Q Target

To further improve on this other architectures of Deep Q Learning were implemented. Like -
1. Double Deep Q Learning
2. Dueling Deep Q Learning
3. Dueling Double Deep Q Learning

![Deep Q Learning Graph](./images/plot1.png)

Obtained Average Score of 15.3/21.0 and best score of 20.0/21.0 in just 250 games
