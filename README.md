# Restricted Boltzmann Machine from Scratch

This project implements a Restricted Boltzmann Machine (RBM) from scratch and applies it to the MNIST dataset. The main steps are as follows:

1. **Data Loading and Preprocessing**: The MNIST dataset is loaded using TensorFlow and preprocessed by normalizing the data and transforming it into binary vectors.
2. **RBM Implementation**: A custom `RBM` class is created to implement the RBM. This class includes initialization of parameters, weights, and biases, calculation of neuron activation probabilities, and update of weights and biases using stochastic gradient descent.
3. **Training and Evaluation**: The RBM is trained using the `train` method, and its performance is evaluated by visualizing the reconstruction of test images and the learned features.

The code and results are provided in the Jupyter notebook and a PDF présentation. The project demonstrates how to implement an RBM from scratch and apply it to a real-world dataset.

Dependencies:

* NumPy
* TensorFlow
* Matplotlib
