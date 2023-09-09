## Overview

This project implements a regression model to estimate knee joint forces using Keras and scikit-learn. It demonstrates techniques like cross-validation and learning curve visualization for model optimization.

## Code 

The `ANN Optimization and Evaluation.ipynb` script defines and evaluates a neural network model to estimate knee joint forces from input biomechanical data. The model is evaluated using repeated k-fold cross-validation to compute performance metrics like MAE.

The next script generates learning curves of model training and validation loss. This provides insight into model convergence and overfitting.

## Usage

The scripts are designed to work together to optimize and evaluate the knee force estimation model:

The model takes in biomechanical data like EMG as the input X. The target y is the 3D knee joint force measurements.

## Installation

Requires Python 3.6+ and these libraries:

- NumPy, Pandas
- scikit-learn, Keras 
- Matplotlib

Use `pip install -r requirements.txt`

## Results

The scripts output model evaluation metrics like MAE along with learning curve plots. Example results are provided in `results/`.

## Contributing 

Contributions welcome! Some ideas:

- Additional models for knee force estimation
- Different evaluation metrics and visualizations
- Experiments on various biomechanical datasets

Let me know if any part of the README needs more detail.
