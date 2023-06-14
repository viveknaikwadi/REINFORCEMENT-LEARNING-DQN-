# REINFORCEMENT-LEARNING-DQN-
Reinforcement Learning (DQN) is a general framework where agents learn to perform actions in an environment so as to maximize a reward. The two main components are the environment, which represents the problem to be solved, and the agent, which represents the learning algorithm.
The agent and environment continuously interact with each other. At each time step, the agent takes an action on the environment based on its policy  , where  is the current observation from the environment, and receives a reward  and the next observation from the environment. The goal is to improve the policy so as to maximize the sum of rewards (return).

The Cartpole environment:- 

A pole is attached to a cart, which can move along a frictionless track. The pole starts upright and the goal is to prevent it from falling over by controlling the cart.
The observation from the environment  is a 4D vector representing the position and velocity of the cart, and the angle and angular velocity of the pole.

The agent can control the system by taking one of 2 actions 

: push the cart right (+1) or left (-1).
A reward is provided for every timestep that the pole remains upright. The episode ends when one of the following is true:

the pole tips over some angle limit
the cart moves outside of the world edges
128 time steps pass.
