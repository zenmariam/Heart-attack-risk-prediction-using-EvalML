# Heart-attack-risk-prediction-using-EvalML
 
## Heart Attack Risk Prediction using EvalML

# Overview

This repository hosts a project focused on predicting the risk of a heart attack in individuals using Automated Machine Learning techniques, specifically EvalML. The primary aim is to develop a robust predictive model that can accurately classify whether a person is at risk of a heart attack based on various health-related features.

# Understanding the Dataset

The dataset includes the following features:

1. Age: Age of the patient
2. Sex: Sex of the patient
3. exang: Exercise-induced angina (1 = yes; 0 = no)
4. ca: Number of major vessels (0-3)
5. cp: Chest Pain type
--Value 0: Typical angina
--Value 1: Atypical angina
--Value 2: Non-anginal pain
--Value 3: Asymptomatic
6. trtbps: Resting blood pressure (in mm Hg)
7. chol: Cholesterol in mg/dl fetched via BMI sensor
8. fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
9. rest_ecg: Resting electrocardiographic results
--Value 0: Normal
--Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
--Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
10. thalach: Maximum heart rate achieved
11. target:
--0 = Less chance of heart attack
--1 = More chance of heart attack

# Usage

1. Load the dataset and understand the distribution of features.
2. Preprocess the data to handle missing values and encode categorical variables.
3. Utilize EvalML to automatically perform feature engineering, model selection, and hyperparameter tuning.
4. Evaluate the model's performance using appropriate metrics.
5. Interpret the results and make predictions on new data.