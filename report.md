### The Environment 
  
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.


A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The **state space** has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

**Action Space**

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Learning Algorithm 

For this project I have implemented Q-Learning algorithm. 
Implemented 2 agents DQN and DDQN 
DDQN performed better than DQN with the same hyperparameters

The model's architecture consists of 
- FC layer1 of 64 units -> relu
- FC layer2 of 64 units -> relu
- 

**Solved the environment in 387 episodes with DDQN Agent**

## Plot of Rewards

![plot rewards](https://github.com/twishasaraiya/drlnd-p1-navigation/blob/master/plot_rewards.png)

### Future Work

- Prioritized Experience Replay
- Dueling Networks

