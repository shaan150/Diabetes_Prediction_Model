# Diabetes Analysis and Prediction

## Overview
This project focuses on analyzing and predicting diabetes outcomes using a dataset containing various health indicators. The analysis includes data preprocessing, exploratory data analysis, correlation analysis, and the implementation of machine learning models to predict diabetes.

## Project Structure
The project is organized as follows:

- **Data Preprocessing**: Handling missing values, scaling features, and preparing the data for analysis.
- **Exploratory Data Analysis (EDA)**: Descriptive statistics, visualizations, and initial insights.
- **Correlation Analysis**: Examining relationships between variables using a heatmap.
- **Predictive Modeling**: Implementing and evaluating various machine learning models.

## Notebooks
- **Diabetes_Analysis.ipynb**: The main notebook containing all steps of the project from data loading, preprocessing, EDA, correlation analysis, to model training and evaluation.

## Requirements
To run the notebook, you need the following Python libraries:
```bash
matplotlib
pandas
numpy
seaborn
scikit-learn
```

You can install the necessary libraries using:
```bash
pip install -r requirements.txt
```

## Data
The dataset used in this project is `Healthcare-Diabetes.csv`, which contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1)

## Analysis and Findings
### Descriptive Statistics
- Highlighted differences in glucose and insulin levels between individuals with and without diabetes.
- Observed the interplay between age and pregnancy frequency, suggesting a life-stage-related dimension to diabetes risk.

### Correlation Analysis
- Strong correlations between glucose, insulin, and diabetes outcomes.
- The correlation matrix and heatmap provided insights into the relationships between various health indicators.

### Predictive Modeling
- Implemented several machine learning models including Decision Tree, Random Forest, Support Vector Machine (SVM), and Linear Regression.
- Evaluated models using metrics such as accuracy, precision, recall, F1-score, mean squared error, and R² score.

## Results
The analysis and models provide a comprehensive understanding of the factors influencing diabetes and the effectiveness of different predictive techniques. The Random Forest classifier achieved the highest accuracy in predicting diabetes outcomes.

## References
- Relevant literature and studies used to inform the analysis and modeling steps are cited within the notebook.
