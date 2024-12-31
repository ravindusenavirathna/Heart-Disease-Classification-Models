# Heart Disease Classification Models

This repository demonstrates the implementation and evaluation of two machine learning models—**Logistic Regression** and **Random Forest Classifier** for predicting heart disease. It includes data preprocessing, exploratory data analysis (EDA), model training, testing, and statistical evaluation of model performance using permutation tests.

## Features

- **Data Preprocessing**: Handling numerical and categorical features using scaling and one-hot encoding.
- **Exploratory Data Analysis (EDA)**:
  - Scatterplot Matrix
  - Correlation Matrix Heatmap
  - Parallel Coordinates Plot
- **Machine Learning Models**:
  - Logistic Regression: A baseline linear model.
  - Random Forest Classifier: A non-linear ensemble model.
- **Model Evaluation**:
  - Accuracy scores for training and testing datasets.
  - Statistical significance test (Permutation Test) to compare model performance.
- **Visualization**:
  - Distribution of feature relationships.
  - Histogram of accuracy differences from the permutation test.

## Results Summary

- Logistic Regression: 
  - Training Accuracy: 87%
  - Testing Accuracy: 88%
- Random Forest:
  - Training Accuracy: 93%
  - Testing Accuracy: 90%
- Statistical Significance:
  - Observed Accuracy Difference: 0.0195
  - P-value: 0.7467
  - Conclusion: No statistically significant difference between the models.

## Requirements

- Python 3.8+
- Required libraries (install via pip):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ravindusenavirathna/Heart-Disease-Classification-Models.git
   cd Heart-Disease-Classification-Models
