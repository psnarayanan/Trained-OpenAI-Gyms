# Atari Breakout Training
## Description
This project trains and evaluates an agent in the Atari Breakout environment using the Advantage Actor-Critic (A2C) algorithm. The training logs and saved models are organized in the Logs and Saved Models directories, respectively.

## Directory Structure
AtariBreakout_Training/
    Logs/
        A2C_1/
        A2C_2/
        A2C_3/
        A2C_4/
        A2C_5/
    Saved Models/
AtariBreakout.ipynb

## Usage
Run the AtariBreakout.ipynb notebook to train and evaluate the agent.

# Atari Pong Training
## Description
This project trains and evaluates an agent in the Atari Pong environment using the Proximal Policy Optimization (PPO) algorithm. The training logs and saved models are organized in the Logs and Saved Models directories, respectively.

## Directory Structure
AtariPong_Training/
    Logs/
        PPO_1/
        PPO_2/
        PPO_3/
    Saved Models/
pongAI.ipynb

## Usage
Run the pongAI.ipynb notebook to train and evaluate the agent.

# Cartpole Training
## Description
The Jupyter Notebook will train and evaluate an agent in CartPole-v0 (OpenAI Gym) environment via Proximal Policy Optimization (PPO) algorithm.

A reward of +1 is provided for every step taken, and a reward of 0 is provided at the termination step. The state space has 4 dimensions and contains the cart position, velocity, pole angle, and pole velocity at tip. Given this information, the agent has to learn how to select the best actions. Two discrete actions are available, corresponding to:

0 - 'Push cart to the left'
1 - 'Push cart to the right'
For more details about the cartpole environment, see CartPole-v0.

## Directory Structure
Cartpole_Training/
    Logs/
        PPO_1/
        PPO_2/
        PPO_3/
    Saved Models/
CartPole.ipynb

## Usage
Run the CartPole.ipynb notebook to train and evaluate the agent.

# Lunar Landing Training
## Descrption
This project trains and evaluates an agent in the Lunar Lander environment using the Proximal Policy Optimization (PPO) algorithm. The training logs and saved models are organized in the Logs and Saved Models directories, respectively.

## Directory Structure
Lander_Training/
    Logs/
        PPO_1/
        PPO_2/
        PPO_3/
    Saved Models/
Lander.ipynb

## Usage
Run the Lander.ipynb notebook to train and evaluate the agent.

# Additional Information
## Dependencies
All projects use the following dependencies:

```
gym
stable-baselines3
numpy
matplotlib
pandas
torch
pyglet
```

Install the dependencies using:
```
pip install stable-baselines3 gym numpy matplotlib pandas torch pyglet
```

## Common Functions
- evaluate_policy(model, env, n_eval_episodes=10, render=True): Evaluates the trained model.
- env.reset(): Resets the environment to the initial state.
- env.step(action): Takes an action in the environment.
- env.render(): Renders the environment.

## Logging & Saving Models
- Logs are saved in the Logs directory.
- Models are saved in the Saved Models directory.

## Running Notebooks
Open the respective Jupyter Notebook (.ipynb file) and run all cells to train and evaluate the agent.