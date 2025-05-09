# Handwritten Digit Recognition | Using Deep Learning

This project implements a neural network to recognize handwritten digits from the MNIST dataset. It demonstrates the application of deep learning techniques for image classification tasks using Python and TensorFlow/Keras.

### Features

* Utilizes the MNIST dataset of 70,000 grayscale images of handwritten digits (28x28 pixels)
* Constructs a multi-layer neural network with fully connected (dense) layers
* Implements data normalization and preprocessing for improved model performance
* Includes dropout regularization to reduce overfitting
* Evaluates model accuracy using validation and test datasets
* Provides a clear training pipeline and visualization of training metrics

### Technologies Used

* Python 3.1.1
* TensorFlow / Keras
* NumPy
* Matplotlib (for result visualization)

### Getting Started

1. Clone the repository: git clone https://github.com/yourusername/handwritten-digit-recognition.git
   cd handwritten-digit-recognition

2. Install the required packages:
   pip install -r requirements.txt
  

### Dataset

This project uses the publicly available [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which is loaded directly via Keras datasets.

### Results

The trained model achieves high accuracy of 97.4% on the test set, demonstrating effective digit classification. Sample predictions and confusion matrix visualizations are included in the repository.
