# Follow Up Treatment Prediction

## Introduction

This project’s objective is to predict whether the patient’s treatment will be done in an inpatient or outpatient stay using the patient’s age, gender, and lab test results. The dataset can be found [here](https://www.kaggle.com/datasets/saurabhshahane/patient-treatment-classification).The CSV file can be downloaded and read into python. 
This project consists of 3 programs with the following sections:
 - Data Preparation
 - Exploratory Data Analysis
 - Modeling

## Data Preparation
Data prep includes handling for missing and duplicate data (if applicable) and one-hot encoding categorical features. Prep also includes dropping patients with age under 18.

## Exploratory Data Analysis
Explores the dataset visually with histograms, scatterplots, bar charts, and correlation heatmap.

## Modeling
Fit logistic regression, random forest, decision tree, and KNN classifier models and determine which best fits based on model statistics.
