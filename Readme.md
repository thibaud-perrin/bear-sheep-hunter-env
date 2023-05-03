# Reinforcement Learning with Q-Learning Project
This project aims to implement a Q-learning algorithm to solve an environment with 3 blobs: a bear, a sheep, and a hunter. The bear has to catch the sheep while avoiding the hunter, both of which move randomly. The bear moves based on Q-learning.

<div align="center">
    <img src="./img/bear_sheep_hunter.gif" width="50%" />
</div>

## Usage
To run the project, open the `QLEnv.ipynb` notebook and execute the code. This will create the environment and train the Q-learning algorithm. Once the algorithm is trained, it will save the Q-table to `saves/qtable-1683106349.pickle`.

## Project Structure
- img
  - bear_sheep_hunter.gif: gif image presenting the environment
- saves
  - qtable-1683106349.pickle: saved Q-table after training
- sprites
  - sprites.png: sprites used in the environment
  - Sprites.psd: Photoshop file containing the sprites
- Pipfile: file containing the dependencies used in the project
- Pipfile.lock: file containing the exact versions of the dependencies used in the project
- QLEnv.ipynb: Jupyter notebook containing the code for the environment and the Q-learning algorithm
- Readme.md: this file
- requerements.txt: file containing the dependencies used in the project

## Requirements
This project requires the following dependencies:

- numpy
- jupyterlab
- matplotlib
- six21
- pyglet
- imageio
- imageio[ffmpeg]
- scipy
- Pillow
- opencv-python
- ipython
- nodejs-bin
- jupyter_contrib_nbextensions



## Installation
This project requires Python 3.11 or higher. To install the required dependencies, please run:
```
pipenv shell
pipenv install --requirements "requirements.txt"
```
to install ipython
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```
to fixed jupyter_nbextensions_configurator error
```
jupyter nbextensions_configurator enable --user
```
