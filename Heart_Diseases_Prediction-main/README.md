# Predicting Heart Diseases using Machine Learning

This project explores the application of Python-based Machine Learning and Data Science libraries to create a predictive model for heart diseases based on medical attributes.

## Table of Contents
1. [Problem Definition](#1-problem-definition)
2. [Data](#2-data)
3. [Evaluation](#3-evaluation)
4. [Features](#4-features)
5. [Modelling](#5-modelling)

## 1. Problem Definition

### In a Statement

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original data is sourced from the Cleveland data from the UCI Machine Learning Repository and is also available on Kaggle.

- [UCI Machine Learning Repository - Heart Disease Data](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- [Kaggle - Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

## 3. Evaluation

The project aims to achieve a minimum of 95% accuracy in predicting heart disease during the proof of concept.

## 4. Features

### Data Dictionary

1. **age:** Age of the individual.
2. **sex:** Gender of the individual (1 = male, 0 = female).
3. **cp:** Chest-pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptotic).
4. **trestbps:** Resting Blood Pressure (mmHg) with values above 130-140 typically indicating concern.
5. **chol:** Serum Cholesterol (mg/dl).
6. **fbs:** Fasting Blood Sugar (1 = true, 0 = false) with levels above 120mg/dl indicating diabetes.
7. **restecg:** Resting ECG (0 = normal, 1 = having ST-T wave abnormality, 2 = left ventricular hypertrophy).
8. **thalach:** Max heart rate achieved.
9. **exang:** Exercise-induced angina (1 = yes, 0 = no).
10. **oldpeak:** ST depression induced by exercise relative to rest.
11. **slope:** Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).
12. **ca:** Number of major vessels (0–3) colored by fluoroscopy.
13. **thal:** Displays the thalassemia (1, 3 = normal, 6 = fixed defect, 7 = reversible defect).
14. **target:** Indicates whether the individual has heart disease (1 = yes, 0 = no).

## 5. Modelling

The data is split into training and test sets, and various Machine Learning models will be used to build the predictive model. These models include:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

Evaluation metrics will be used to assess the performance of each model, including accuracy, precision, recall, and F1-score.

## Acknowledgments
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)
