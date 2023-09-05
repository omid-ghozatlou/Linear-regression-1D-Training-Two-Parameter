# Linear-regression-1D-Training-Two-Parameter
In this lab, you will train a model with PyTorch by using the data that we created. The model will have the slope and bias. And we will review how to make a prediction in several different ways by using PyTorch.
This script is designed to demonstrate the training process of a simple linear regression model. The script includes visualization components to help understand how the model learns over iterations.

## Prerequisites

Before running this script, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- mpl_toolkits (mplot3d)

You can install these dependencies using pip:

```bash
pip install torch numpy matplotlib
```

## Script Overview

### Purpose

The script aims to showcase the training of a linear regression model to fit noisy data points.

### Script Components

1. Import necessary libraries: The script begins by importing required Python libraries, including PyTorch, NumPy, and Matplotlib.

2. Data Preparation: It creates synthetic data by defining a linear function with noise.

3. Model Definition: The forward function and loss function (Mean Squared Error) are defined.

4. Training Loop: The training loop is implemented, which includes:
   - Making predictions using the current model parameters.
   - Calculating the loss.
   - Updating the model parameters using gradient descent.
   - Visualizing the training process with plots at specified intervals.

5. Visualization: The script uses the `plot_error_surfaces` class to visualize the cost/total loss surface, contour plots, and the data space iteration.

6. Plotting Loss: After training, the script plots the loss over iterations.

### Usage

To run the script, follow these steps:

1. Make sure you have installed the required dependencies.

2. Execute the script using Python:

   ```bash
   python your_script_name.py
   ```

3. Observe the training process through the generated plots and the loss curve.

### Customization

You can customize the script for your own datasets and experiments by modifying the following:

- Adjust the data generation process by changing the function `f` and the noise level in the `Y` calculation.
- Modify the model architecture by changing the forward function and loss function.
- Experiment with different hyperparameters such as learning rate, number of training iterations, and the initial values of `w` and `b`.

### Acknowledgments

This script was created for educational purposes and is inspired by the work of various machine learning and deep learning tutorials.

Feel free to explore and experiment with the script to gain a better understanding of linear regression and gradient descent optimization.
