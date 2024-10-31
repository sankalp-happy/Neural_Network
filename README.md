# Neural Network from Scratch

This project implements a neural network from scratch using Python and popular libraries such as NumPy and Matplotlib. The network is trained on a spiral dataset to classify data points into three classes. The implementation includes dropout layers to prevent overfitting and uses the Adam optimizer for training.

## Features

- Custom implementation of neural network layers and activations
- Dropout layers to prevent overfitting
- Adam optimizer for efficient training
- Training with and without dropout for comparison
- Visualization of training progress

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- tqdm

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/NeuralNetwork_from_scratch.git
    cd NeuralNetwork_from_scratch
    ```

2. Install the required packages:
    ```sh
    pip install numpy matplotlib tqdm
    ```

## Usage

1. Run the training script:
    ```sh
    python NeuralNetwork_from_scratch.ipynb
    ```

2. The script will train the network with and without dropout and plot the training progress.

## Project Structure

- `NeuralNetwork_from_scratch.ipynb`: Main script for training the neural network and plotting results.
- `README.md`: Project documentation.

## Example Output

The training script will output the classification error and loss during training and plot the training progress with and without dropout.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.