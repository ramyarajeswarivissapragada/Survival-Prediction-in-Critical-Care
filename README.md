# Survival Prediction in Critical Care

## Project Overview
This machine learning project focuses on developing advanced mortality prediction models for Intensive Care Unit (ICU) patients using comprehensive medical data analysis and advanced predictive techniques.

## Project Objectives
- Improve upon traditional APACHE scoring system limitations
- Develop more personalized and accurate mortality prediction models
- Address class imbalance in medical datasets
- Identify key predictors of hospital mortality

## Methodology

### Data Preprocessing
- Dataset: 91,713 medical records with 84 features
- Comprehensive data cleaning and preparation
- Advanced feature selection and imputation strategies
- Handling of missing data and class imbalance

### Resampling Techniques
- SMOTE (Synthetic Minority Oversampling Technique)
- SMOTE + Tomek Links
- ADASYN (Adaptive Synthetic Sampling)

### Machine Learning Algorithms
- Random Forest Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Cox Proportional Hazards Model

## Key Achievements
- Improved minority class F1 score from 0.44 to 0.56 (27% increase)
- Developed survival model with 0.91 concordance index
- Identified critical mortality predictors:
  * apache_4a_hospital_death_prob
  * Patient age
  * Ventilator status

## Managerial Insights
- Advanced risk stratification for critical care patients
- Data-driven resource allocation in hospital settings
- Proactive intervention strategies for high-risk patients

## Technologies Used
- Python
- Machine Learning Libraries
- Survival Analysis Techniques
- Data Preprocessing Tools
