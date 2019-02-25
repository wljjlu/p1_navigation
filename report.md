# Report

In this project, the learning algorithm of deep Q-networks has been implemented to solve the navigation problem.

## Vanilla DQN

### Neural Network Architecture

- Input Layer: 37
- Fully connected Layer 1: 64 (with relu as activation)
- Fully connected Layer 2: 64 (with relu as activation)
- Output Layer: 4

### Hyper-parameters

- Replay Memory Size = 1e5
- Batch Size = 64
- GAMMA = 0.99
- TAU = 1e-3
- Learning Rate =5e-4
- Target Network Update Interval = 4

### Plot of Rewards

![Vanilla DQN Scores][images/scores.png]

Vanilla DQN solved the problem in 600 episodes.

## Future Improvement

- Fine tuning hyper parameters to get better performance
- Implement Deep Q-Learning such as using Double DQN, Prioritized Experience Replay and Dueling DQN
