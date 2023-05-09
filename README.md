# Unsupervised Learning Algorithms: A Hands-On Exploration

This project explores different methods of solving Markov Decision Processes (MDP) problems. One MDP is slected such that it has a small number of states while the other has a large number of states.
Both MDPs are solved using 3 different algorithms. 
Problems have varying size (small and large) and type (Grid world and Non-grid world)

## Datasets

The two MDP used in this project are:

1. **[Frozen Lake problem from OpenAI gym environment](https://gym.openai.com/envs/FrozenLake-v0)**

2. **[Forest management problem from mdptoolbox](https://gym.openai.com/envs/FrozenLake-v0)**
## Algorithms

The following unsupervised learning algorithms were used in this project:

1. **Value Iteration**
2. **Policy Iteration**
3. **Q-Learning**


## Results

The results of applying these algorithms on the two problems are discussed in the file `analysis.pdf`

## Requirements

To run the code in this repository, you will need the packages listed in requirements.txt
To install the required packages, run the following command: 
```sh
pip install -r requirements.txt
```
Additionally for the Forest management problem  the code from the following repository need to be cloned to working directory:
```sh
git clone https://github.com/hiive/hiivemdptoolbox
```
Finally the `mdptoolbox-hiive` from the cloned repository need to be intalled:

```sh
pip install mdptoolbox-hiive
```
## Usage

1. Clone this repository and the required repository to your local machine.
2. Navigate to the cloned repository.
3. Open the Jupyter notebooks in your web browser to explore the results.

