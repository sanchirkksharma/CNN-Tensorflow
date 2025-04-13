# CNN-Tensorflow
**Handwritten Digits Classification using TensorFlow:**

This project demonstrates a basic neural network model built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. It includes both a simple logistic regression and a multi-layer neural network using ReLU activation.

**Project Structure:**
1. handwritten_digits_classification.ipynb – Jupyter notebook with step-by-step implementation
2. MNIST dataset – Loaded directly using Keras
3. Visualization – Includes heatmap of confusion matrix for prediction analysis

**Model Summary:**

**-->Model 1:**

Logistic Regression Architecture: Single dense layer with sigmoid activation

Input: Flattened 28x28 images (784 features)

Accuracy: Evaluated on test data

**-->Model 2:**

Deep Neural Network Architecture: Dense layer with 100 neurons and ReLU activation, Output layer with 10 neurons (one per digit) and sigmoid activation

Loss Function: Sparse Categorical Crossentropy

Optimizer: Adam

Accuracy: Improved over Model 1

**How to Run:**

--> Clone the repository:
git clone https://github.com/sanchirkksharma/CNN-Tensorflow.git
cd CNN-Tensorflow

--> Open the notebook:
jupyter notebook handwritten_digits_classification.ipynb
Run all cells to see data loading, preprocessing, model training, evaluation, and visualization.

