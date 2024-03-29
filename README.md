# Regression-Techniques-and-Regularization-with-the-Diabetes-Dataset

## Overview
This repository delves into regression problems using the Diabetes dataset, highlighting techniques to address underfitting and overfitting through regularization methods. 

## Getting Started
### Installation
To run the notebook and replicate the findings, ensure you have the following Python packages installed:
```bash
pip install torch 
pip install pandas 
pip install matplotlib 
pip install seaborn 
pip install scikit-learn
```

### Dataset
The Diabetes dataset, accessible here, comprises ten baseline variables, age, sex, body mass index, average blood pressure, and six blood serum measurements obtained for each of n = 442 diabetes patients, along with a response of interest, a quantitative measure of disease progression one year after baseline.


### Implementation Highlights
- **Linear Regression**: A foundational approach to modeling the relationship between the dataset's features and the response variable.
- **Data Normalization**: Standardization of dataset features to have zero mean and unit variance, facilitating model training.
- **Gradient Descent Optimization**: Custom implementation of gradient descent to update model weights based on the loss gradient.
- **Regularization Techniques**: Application of L2 regularization to penalize large weights, addressing overfitting by including a regularization term in the loss function.
- **Model Evaluation**: Assessment of model performance through mean squared error on the test set, providing insight into the model's predictive accuracy.

### Experiments and Observations
- The project explores the effects of different learning rates and regularization strengths on model performance, demonstrating the trade-offs between bias and variance.
- Regularization proves effective in mitigating overfitting, especially in scenarios where the model complexity is high relative to the amount of training data.
- The choice of learning rate significantly impacts the convergence of gradient descent, with too high a rate causing instability and too low a rate resulting in slow convergence.
