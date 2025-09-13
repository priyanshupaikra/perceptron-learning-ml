# Perceptron Implementations

This repository contains implementations of both Single-Layer and Multi-Layer Perceptrons in Python for educational purposes.

## Notebooks

1. `single_layer_perceptron.ipynb` - Original single-layer perceptron implementation
2. `multi_layer_perceptron.ipynb` - Multi-layer perceptron with hidden layers
3. `perceptron_comparison.ipynb` - Side-by-side comparison of both approaches

## About Perceptrons

A perceptron is a supervised learning algorithm used for classification which inputs a vector of numbers, applies weights to the inputs and uses an activation function to generate the result.

- **Single-Layer Perceptron (SLP)**: Simple linear classifier that can only learn linearly separable patterns
- **Multi-Layer Perceptron (MLP)**: Neural network with one or more hidden layers that can learn complex, non-linear patterns

## Dataset

We use the Iris dataset with 3 classes:
- Class 0: Iris-setosa
- Class -1: Iris-versicolor  
- Class 1: Iris-virginica

The dataset has 4 features: sepal length, sepal width, petal length, and petal width.

## Requirements

(This program was implemented in Jupyter notebooks)

- Python 3
- Jupyter
- Numpy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

It is recommended to install Anaconda platform as it comes with all essential libraries required for data science.

## Results

The Multi-Layer Perceptron significantly outperforms the Single-Layer Perceptron on the Iris dataset:
- Single-Layer Perceptron: ~23% accuracy - may change; in my case it was always give different 
- Multi-Layer Perceptron: ~90%+ accuracy

This demonstrates the power of deep learning architectures to model complex, non-linear relationships.

## References

- <http://homepages.gold.ac.uk/nikolaev/311perc.htm>
- <http://www.cs.stir.ac.uk/courses/ITNP4B/lectures/kms/2-Perceptrons.pdf>
- <https://en.wikipedia.org/wiki/Perceptron>
  
_You can read about McCulloch-Pitts Neurons here:_

- <http://www.mind.ilstu.edu/curriculum/modOverview.php?modGUI=212>
