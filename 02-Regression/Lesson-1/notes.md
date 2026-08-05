
# Lesson 1: Get Started with Python and Scikit-learn for Regression Models

## Overview

In this lesson, we set up a machine learning environment and build our first regression model using Python and Scikit-learn.

## Learning Goals

- Configure Python for machine learning.
- Work with Jupyter Notebooks.
- Install and use Scikit-learn.
- Build a simple Linear Regression model.

## Tools Used

- Python
- Jupyter Notebook
- Scikit-learn
- NumPy
- Matplotlib

## Machine Learning Environment

Jupyter Notebook is an interactive environment used by data scientists to:

- Write Python code
- Add explanations using Markdown
- Test ML experiments easily

## Scikit-learn

Scikit-learn is a Python machine learning library used for:

- Data preprocessing
- Model training
- Model evaluation
- Building regression and classification models

## Regression

Regression is a supervised learning technique used to predict numerical values.

Examples:

- House price prediction
- Weather forecasting
- Disease progression prediction

## Linear Regression Workflow

1. Load dataset
2. Select features (X) and target (y)
3. Split data into training and testing sets
4. Train the model using `model.fit()`
5. Make predictions using `model.predict()`
6. Visualize results

## Dataset Used

The lesson uses the Scikit-learn Diabetes dataset:

- 442 samples
- 10 feature variables
- Target: Disease progression

## Important Concepts

**Feature (X):**
Input variables used to train the model.

**Target (y):**
The value the model tries to predict.

**Training Data:**
Data used to teach the model.

**Testing Data:**
New data used to evaluate model performance.

## Libraries Imported

```python
import matplotlib.pyplot as plt
import numpy as np
from sklearn import datasets, linear_model, model_selection
```
