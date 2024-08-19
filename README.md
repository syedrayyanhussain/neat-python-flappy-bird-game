# Flappy Bird Game with NEAT

This repository contains a Flappy Bird game implemented in Python using Pygame and NEAT (NeuroEvolution of Augmenting Topologies). The game features a neural network that learns to play Flappy Bird through evolutionary algorithms.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Flappy Bird Game**: A classic Flappy Bird game implemented using Pygame.
- **Neural Network AI**: Utilizes NEAT to evolve a neural network that learns to play the game.
- **Customizable Settings**: Adjust the game and neural network settings through configuration files.

## Installation

To run this project, you need to have Python and the required libraries installed. Follow these steps to set up the project:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/flappy-bird-neat.git
    cd flappy-bird-neat
    ```

2. **Create a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install pygame neat-python
    ```

4. **Download or place the image assets** into the `imgs` directory. Ensure the following images are present:

    - `bird1.png`
    - `bird2.png`
    - `bird3.png`
    - `pipe.png`
    - `base.png`
    - `bg.png`

    Update the `images_path` variable in the code to the path where these images are stored.

## Configuration

The NEAT configuration is specified in `config.txt`. You can adjust the parameters in this file to experiment with different settings for the neural network and evolutionary process.

## Usage

To start the game and train the neural network:

1. **Run the main script:**

    ```bash
    python main.py
    ```

2. The game window will appear, and the NEAT algorithm will start evolving neural networks to play the game. The training process will run for a specified number of generations as defined in the `run` function of `main.py`.

3. You can monitor the fitness of each genome in the console output. The `winner` genome's performance will be printed at the end of the training process.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.


