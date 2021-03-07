# Stock Prediction with Reinforcement Learning
(NY Machine Learning Workshop)

## Installation
Have an Anaconda environment installed, then:

```bash
conda create -n rl python=3 jupyterlab numpy pandas matplotlib
conda activate rl
```

## Q-Learning Introduction
https://towardsdatascience.com/a-beginners-guide-to-q-learning-c3e2a30a653c

## Notebooks
```
jupyter lab
```

Open notebooks:
`reinforcement-learning-1.ipynb`
`reinforcement-learning-2.ipynb`

## Advanced - Deep Reinforcement Learning
```
conda install -c conda-forge tensorflow # or tensorflow-gpu

cd ..
git clone https://github.com/matthiasplappert/keras-rl.git
cd keras-rl
python setup.py install

cd ../market-rl
conda install -c conda-forge gym
jupyter lab
```

Open notebook: `deep-reinforcement-learning.ipynb`

https://towardsdatascience.com/deep-reinforcement-learning-for-automated-stock-trading-f1dad0126a02
