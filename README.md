# Learning_Activation_Project
## 1. Overview
This project implements a neural network model with a custom activation function 𝑔(𝑥)=𝑘0+𝑘1𝑥g(x)=k0+k1x. The activation function learns its parameters during training using backpropagation, improving adaptability to various datasets.

## 2. Features
1.Custom trainable activation function.
2.Simple feedforward neural network with 1-2 hidden layers.
3.Training and evaluation on the Iris dataset (can be adapted to other datasets).
4.Visualization of training progress (accuracy and loss plots).
5.Displays learned parameters of the custom activation function.

## 3. Prerequisites
Python 3.8 or later.
Libraries like numpy,pandas,sklearn,tensorflow

## 4. Dataset
The Iris dataset is used as an example.
The dataset is preprocessed with feature scaling and one-hot encoding.

## 5. How to Run
Clone the repository or download the script.
Ensure the prerequisites are installed.
Run the script

## 6. The script will:
Train the model on the Iris dataset.
Display training/validation accuracy and loss plots.
Print the learned parameters k0 and k1
​
## 7. Customization
Replace the Iris dataset with any other dataset (e.g., MNIST, Breast Cancer):
Update the data loading and preprocessing sections.
Adjust model architecture (e.g., number of hidden layers, neurons).

## 8. Outputs
Training and validation accuracy and loss plots.
Console output of the test set performance which is 94.1% accuracy for layer1 and 93.2% for layer 2.
