# Heart Failure Prediction using Logistic Regression

## Overview

This project analyzes and predicts heart failure using Logistic Regression. The dataset includes patient medical records with factors such as age, diabetes, anemia, and blood pressure. The goal is to predict the likelihood of heart failure based on these factors.

## Dataset Information

1.Sex - Gender of patient (Male = 1, Female = 0)
2.Age - Age of the patient
3.Diabetes - (0 = No, 1 = Yes)
4.Anaemia - (0 = No, 1 = Yes)
5.High blood pressure - (0 = No, 1 = Yes)
6.Smoking - (0 = No, 1 = Yes)
7.DEATH EVENT - (0 = No, 1 = Yes) - Target variable

## Project Structure

1.heart_failure_clinical_records_dataset.csv` - Dataset file
2.heart_failure_analysis.py` - Python script for analysis and prediction
3.README.md` - Project documentation  

## Features Implemented

Data Visualization:
1. Pie chart for diabetes distribution
2. Pie chart for death event analysis
3. Heatmap to visualize feature correlation
Machine Learning Model:
 1.Logistic Regression for heart failure prediction
 2.Confusion matrix to evaluate model performance

## Usage

1.The script reads the dataset, performs exploratory data analysis (EDA), and trains a logistic regression model.
2.The model predicts the DEATH EVENT based on selected features (time, ejection fraction, serum creatinine).
3.Accuracy and confusion matrix are displayed to evaluate performance.

## Expected Output

Accuracy Score: Displays the logistic regression accuracy.
Visualizations:
  Pie charts for diabetes and death events.
  Correlation heatmap.
  Confusion matrix.
