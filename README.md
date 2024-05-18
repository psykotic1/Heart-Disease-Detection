# Heart-Disease-Detection

## Overview

This project aims to detect heart disease using three different machine learning algorithms: Logistic Regression, Naive Bayes, and Random Forest. The objective is to compare the performance of these algorithms on a small-sized dataset and determine their effectiveness in predicting heart disease.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
  - [Logistic Regression](#logistic-regression)
  - [Naive Bayes](#naive-bayes)
  - [Random Forest](#random-forest)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Heart disease is a leading cause of mortality worldwide, making early detection crucial. This project leverages machine learning techniques to predict the likelihood of heart disease in patients based on various medical parameters. Using three different algorithms, we aim to understand their strengths and weaknesses in this context.

## Dataset

The dataset used in this project is a small-sized dataset consisting of patient records, including attributes such as age, sex, blood pressure, cholesterol levels, and other relevant medical information. The target variable is the presence or absence of heart disease.

## Algorithms Used

### Logistic Regression

Logistic Regression is a statistical model that uses a logistic function to model a binary dependent variable. It is widely used for binary classification problems.

### Naive Bayes

Naive Bayes is a probabilistic classifier based on Bayes' theorem with strong independence assumptions between features. It is particularly effective for small datasets and high-dimensional data.

### Random Forest

Random Forest is an ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes for classification tasks. It is known for its robustness and accuracy.

## Usage

1. Ensure that the dataset is placed in the appropriate directory (e.g., `data/heart_disease.csv`).
2. Run the Jupyter notebook to execute the project:

    ```bash
    jupyter notebook
    ```

3. Open `Heart_Disease_Detection.ipynb` and run all the cells to train and evaluate the models.

## Results

The performance of each algorithm was evaluated using the accuracy score metric. The results obtained on the small-sized dataset are as follows:

- **Logistic Regression:** The accuracy score achieved is 85.25%.
- **Naive Bayes:** The accuracy score achieved is 85.25%.
- **Random Forest:** The accuracy score achieved is 88.52%.

These results indicate that while Logistic Regression and Naive Bayes performed equally well, the Random Forest algorithm showed a slight improvement in accuracy, suggesting it might be more effective for this particular dataset.

## Conclusion

This project demonstrates the application of Logistic Regression, Naive Bayes, and Random Forest algorithms for heart disease detection. By comparing their performance on a small dataset, we gain insights into their suitability for medical diagnosis tasks.
