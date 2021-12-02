# Python-Rl-Learning

## Get started

Prerequisites:
* Python 3.8+
* [Poetry](https://python-poetry.org)

Install dependencies:
```
poetry install
```

Train agents:
```
poetry run python ppo.py
```

Train agents with experiment tracking (You should have Weights and Biases account for this feature):
```
poetry run python ppo.py --track --capture-video
```

### Atari
Install dependencies:
```
poetry install -E atari
poetry run AutoROM
```
Train agents:
```
poetry run python ppo_atari.py
```
Train agents with experiment tracking (You should have Weights and Biases account for this feature):
```
poetry run python ppo_atari.py --track --capture-video
```
