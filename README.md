# Neural Network Implementation from Scratch

## About the Project

This project is a simple implementation of a feedforward neural network using
Python and NumPy. The main purpose of the project is to understand how a
neural network works internally instead of using libraries such as TensorFlow
or PyTorch.

The network is trained using forward propagation, backpropagation and gradient
descent.

## Dataset

The Iris dataset is used for this project. It contains measurements of iris
flowers such as sepal length, sepal width, petal length and petal width.

For this implementation, two classes are used:

- Iris Setosa (Class 0)
- Iris Versicolor (Class 1)

This makes the problem a binary classification task.

Dataset source:

https://archive.ics.uci.edu/dataset/53/iris

## Neural Network

The network used in this project has:

- 4 input neurons
- 1 hidden layer with 8 neurons
- 1 output neuron

The sigmoid activation function is used in the hidden and output layers.

Binary Cross-Entropy is used as the loss function and gradient descent is used
for training the network.

## Working

The implementation follows these steps:

1. Load the Iris dataset.
2. Select the required two classes.
3. Split the data into training and testing sets.
4. Standardize the input features.
5. Initialize weights and biases.
6. Perform forward propagation.
7. Calculate the loss.
8. Perform backpropagation.
9. Update the weights and biases using gradient descent.
10. Repeat the process for the specified number of epochs.
11. Test the trained model and calculate its accuracy.

## Results

The model performance is checked using:

- Training loss graph
- Test accuracy
- Confusion matrix
- Classification report

The training loss decreases as the model is trained, showing that the network
is learning from the training data.

The final accuracy and confusion matrix obtained from the experiment are
available in the Jupyter/Google Colab notebook.

## Files

`Soham_Sabane_GenerativeAILabAssignment.ipynb` - Main notebook containing
the complete implementation.

`README.md` - Project description and instructions.

## How to Run

The notebook can be opened directly in Google Colab.

1. Open the `.ipynb` file in Google Colab.
2. Run the cells from top to bottom.
3. The dataset will be loaded automatically.
4. The neural network will be trained.
5. The final accuracy, confusion matrix and other results will be displayed.

## Author

**Soham Sabane**

Department: CSE AIML  
Course: Generative AI Lab  
Dataset: Iris Dataset
