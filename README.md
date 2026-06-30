# Student Grade Prediction Using Machine Learning Models

## Overview

This project implements a complete machine learning classification pipeline to predict student grades using academic and behavioral data. The dataset contains 10,000 student records with features such as study hours, attendance percentage, previous GPA, sleep hours, extracurricular participation, and tutoring sessions.

The primary objective is to compare the performance of multiple classification algorithms while implementing the K-Nearest Neighbors (KNN) algorithm entirely from scratch using NumPy.

## Dataset

The dataset includes the following features:

| Feature           | Description                                 |
| ----------------- | ------------------------------------------- |
| study_hours       | Number of hours spent studying              |
| attendance_pct    | Student attendance percentage               |
| previous_gpa      | Previous academic GPA                       |
| sleep_hours       | Average daily sleep hours                   |
| extracurricular   | Participation in extracurricular activities |
| tutoring_sessions | Number of tutoring sessions attended        |
| grade             | Target variable representing student grade  |

## Project Workflow

1. Data Loading and Exploration
2. Missing Value Handling
3. Feature Encoding
4. Feature Scaling (Manual Z-Score Standardization)
5. Train-Test Split
6. KNN Implementation from Scratch Using NumPy
7. Logistic Regression Training
8. Decision Tree Training
9. Random Forest Training
10. Model Evaluation and Comparison
11. Cross-Validation Analysis

## Models Used

* K-Nearest Neighbors (KNN) – Implemented from Scratch
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

## Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* 5-Fold Cross Validation

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Key Learning Outcomes

* Data preprocessing and cleaning
* Feature engineering and scaling
* Implementation of KNN without external libraries
* Classification model training and evaluation
* Performance comparison of machine learning algorithms
* Cross-validation and model assessment

## Repository Structure

```text
├── students_performance.csv
├── assignment.ipynb
├── README.md
└── requirements.txt
```

## Installation

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Running the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook assignment.ipynb
```

3. Run all cells to reproduce the results.

## Results

The project compares KNN, Logistic Regression, Decision Tree, and Random Forest models to determine the most effective approach for student grade prediction. Performance is analyzed using accuracy scores and cross-validation results.

## Author

Muhammad Hasnat Anwar
