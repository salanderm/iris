# Iris Dataset Classification Project

This project implements a classification model for the famous Iris dataset using machine learning. The goal is to classify iris flower species based on sepal and petal measurements.

## Project Overview

### Features:
- **Dataset**: The Iris dataset, containing:
  - **150 samples** across 3 classes (Setosa, Versicolor, Virginica).
  - **Features**: Sepal length, Sepal width, Petal length, Petal width.
- **Model**: Support Vector Machine (SVM) classifier for multi-class classification.
- **Evaluation**: Metrics such as accuracy and a classification report to assess model performance.

## Project Structure

### Notebook
The notebook (`iris.ipynb`) contains:
1. **Data Loading**: Loads the Iris dataset using `sklearn.datasets`.
2. **Data Splitting**: Splits the dataset into training and testing sets.
3. **Model Training**: Trains an SVM classifier on the training data.
4. **Evaluation**: Generates a classification report and calculates accuracy on the test set.
5. **Visualization**: Visualizes decision boundaries or data distributions (if applicable).

## How to Run

1. **Setup**:
   - Install Python and Jupyter Notebook.
   - Install the required libraries:
     ```bash
     pip install pandas matplotlib scikit-learn
     ```

2. **Run the Notebook**:
   - Open `iris.ipynb` in Jupyter Notebook or JupyterLab.
   - Execute the cells sequentially to load data, train the model, and view evaluation results.

3. **Customize**:
   - Modify hyperparameters of the SVM model or explore additional algorithms for comparison.

## Requirements

- Python 3.x
- Libraries: `pandas`, `matplotlib`, `scikit-learn`

## Outputs

- Classification report for the model.
- Accuracy score on the test data.
- Visualizations (if implemented in the notebook).
