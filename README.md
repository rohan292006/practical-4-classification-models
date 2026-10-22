# Practical Assignment 4: Classification Models

## Overview
This project implements and compares four supervised machine learning classification algorithms using Python and scikit-learn.

## Aim
To evaluate SVM, Decision Tree, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes using relevant classification performance metrics.

## Dataset
The project uses the Breast Cancer Wisconsin dataset available through `sklearn.datasets.load_breast_cancer()`.

- Samples: 569
- Features: 30 numerical features
- Classes: Malignant and benign
- Train-test split: 80% training and 20% testing
- Random state: 42

## Algorithms Implemented
1. Support Vector Machine (SVM) with an RBF kernel
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN), with k = 5
4. Gaussian Naive Bayes

## Evaluation Metrics
- Accuracy
- Precision (macro average)
- Recall (macro average)
- F1-score (macro average)
- Log loss

Confusion matrices and classification reports are also generated.

## Technologies Used
- Python
- Google Colab
- scikit-learn
- pandas
- matplotlib

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Run the Python program:

   `python practical4_classification.py`

The program prints model metrics and confusion matrices, generates a comparative bar chart, and saves the results in CSV format.

Alternatively, open the `.ipynb` notebook in Google Colab and execute its cells from top to bottom.

## Output Files
- `classification_model_results.csv`: comparative model metrics
- `classification_model_comparison.png`: performance comparison chart
- `screenshots/`: selected screenshots of actual execution

## Findings
The best-performing model is identified using macro F1-score. The final ranking and metrics should be taken from the actual program execution. The most suitable classifier depends on the dataset, computational cost, interpretability, and the consequences of classification errors.

## Educational Use
This project is intended for academic learning and comparison of machine learning classification algorithms. The cancer dataset results are not intended for clinical diagnosis.
