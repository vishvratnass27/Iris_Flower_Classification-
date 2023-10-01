
# Iris Flower Classification with Machine Learning

![Iris Flower](iris.jpg)

This project focuses on classifying iris flowers into different species using machine learning techniques. The dataset used in this project is the famous Iris dataset, which contains measurements of sepal length, sepal width, petal length, and petal width for three different iris species.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Information](#dataset-information)
- [Data Exploration](#data-exploration)
- [Data Visualization](#data-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Introduction
In this project, we explore the Iris dataset, perform data visualization, and build machine learning models to classify iris flowers into three species: 'Iris-setosa', 'Iris-versicolor', and 'Iris-virginica'. We use various classification algorithms to achieve this task, including Logistic Regression, k-Nearest Neighbors, Decision Trees, and Random Forests.

## Dataset Information
- Dataset Name: Iris Dataset
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target Variable: Species (Categorical)

## Data Exploration
- Investigated the dataset using `dataset.info()` and `dataset.describe()`.
- Checked for null values with `dataset.isnull().sum()`.
- Explored the unique values in the dataset using `dataset.nunique()`.

## Data Visualization
- Created histograms to visualize the distribution of sepal and petal measurements.
- Plotted scatter plots to understand the relationships between different iris species based on sepal and petal characteristics.
- Generated a heatmap to visualize the correlation between features.

## Data Preprocessing
- Encoded the 'species' column using Label Encoding.
- Split the dataset into training and testing sets using `train_test_split`.

## Machine Learning Models
- Trained machine learning models including Logistic Regression, k-Nearest Neighbors, Decision Trees, and Random Forests.
- Evaluated model performance using accuracy scores on both training and testing datasets.

## Results
- Logistic Regression Accuracy: 0.9666666666666667
- k-Nearest Neighbors Accuracy: 0.9833333333333333
- Decision Tree Accuracy: 1.0
- Random Forest Accuracy (Test Set):0.9333333333333333

