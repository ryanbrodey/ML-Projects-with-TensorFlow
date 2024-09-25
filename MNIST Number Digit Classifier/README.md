# Our First Neural Network

This project implements a simple neural network using TensorFlow to classify handwritten digits from the MNIST dataset.

## Overview

In this notebook, we will build a fully connected neural network to classify images of handwritten digits. We will utilize the popular MNIST dataset, which contains 70,000 images of digits (0-9) for training and testing.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup Instructions](#setup-instructions)
3. [How to Run the Notebook](#how-to-run-the-notebook)
4. [Code Explanation](#code-explanation)
5. [Results](#results)
6. [Important Notes](#important-notes)

## Prerequisites

- **Python 3.x**: Ensure you have Python installed. You can check your version using:
  ```bash
  python3 --version
  ```

## Required Libraries

Install the necessary libraries if you haven't already:

```bash
pip install tensorflow matplotlib numpy
```

## Setup Instructions

### Clone the Repository

```bash
git clone https://github.com/yourusername/ML-Projects-with-TensorFlow.git
cd ML-Projects-with-TensorFlow
```

## Open the Notebook

Launch Google Colab and open `OurFirstNeuralNetwork.ipynb`.

## Run the Notebook Cells

Execute each cell in order to build and train the neural network.

## How to Run the Notebook

To run the notebook, you can open it directly via this link:

[Open In Colab](https://colab.research.google.com/github/ryanbrodey/ML-Projects-with-TensorFlow/blob/main/OurFirstNeuralNetwork.ipynb)

## Code Explanation

- **Loading the MNIST Dataset**: The dataset is loaded and split into training and testing sets.
- **Data Normalization**: Pixel values are normalized to be in the range of 0 to 1.
- **Building the Neural Network**: A simple feedforward neural network is constructed using Keras layers.
- **Model Compilation**: The model is compiled with the Adam optimizer and sparse categorical crossentropy loss function.
- **Training the Model**: The model is trained for a specified number of epochs.
- **Evaluation**: The model's performance is evaluated on the test set.

## Results

After training, the model will display its accuracy on the test dataset, and you can inspect the predictions made on the test images.

## Important Notes

- Ensure that you have sufficient RAM and compute resources when training the model.
- Modify the parameters (like epochs, batch size, etc.) to see how they affect the model's performance.








