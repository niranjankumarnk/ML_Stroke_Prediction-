# ML Stroke Prediction

This project aims to predict the likelihood of stroke occurrence in individuals based on various health parameters using machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Dependencies](#dependencies)
- [Workflow](#workflow)
- [Results](#results)

## Introduction

Stroke, also known as a cerebrovascular accident (CVA) or brain attack, is a medical condition in which poor blood flow to the brain causes cell death. Early detection of stroke risk is crucial as it can have severe consequences if untreated. This project utilizes machine learning algorithms to predict the probability of stroke based on health parameters, such as age, gender, hypertension, heart disease, and more. By analyzing these parameters, individuals at higher risk can be identified, enabling early intervention and preventive care.

## Dataset

The dataset used in this project is sourced from [Kaggle]([https://www.kaggle.com](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)/). It has been preprocessed and cleaned to ensure data quality and consistency before model training.
#### Imbalance dataset: ***0 - No stoke***  ***1 - Stroke***

![image](https://github.com/user-attachments/assets/affbc1df-db1c-4da4-84f1-fa821e796b28)
**Balanced the dataset using SMOTE Technique**
## Features

The dataset includes the following features:
- **Age**: Age of the individual.
- **Gender**: Gender of the individual (male/female).
- **Hypertension**: Indicator for hypertension (1 if yes, 0 if no).
- **Heart Disease**: Indicator for heart disease (1 if yes, 0 if no).
- **Marital Status**: Marital status of the individual.
- **Work Type**: Type of work the individual is engaged in.
- **Residence Type**: Type of residence (urban/rural).
- **Average Glucose Level**: Average glucose level in the individual's blood.
- **BMI**: Body Mass Index of the individual.
- **Smoking Status**: Smoking status of the individual (smoker/non-smoker/unknown).

## Dependencies

The following dependencies are required to run the project:
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Workflow
The workflow for this project includes:

- **Data Collection**: Acquiring the dataset from Kaggle.
- **Data Preprocessing**: Cleaning and preparing data for model training.
- **Exploratory Data Analysis (EDA**): Visualizing data patterns and understanding correlations.
- **Feature Engineering**: Enhancing feature representation.
- **Model Selection**: Choosing suitable machine learning models.
- **Model Training**: Training models on the processed data.
- **Model Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.
- **Model Interpretation**: Understanding model predictions.


## Result : 
The machine learning model results demonstrate its ability to predict stroke likelihood based on the provided features. Below is an example result visualization:

![image](https://github.com/user-attachments/assets/b43de0f4-1b9f-4ff6-aee2-3e5710e1ff74)

## Acknowledgments
This project was inspired by the need for early detection of stroke risk factors to improve preventive healthcare.



