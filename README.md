# EduPredict AI

## Student Performance Analytics & Success Prediction System

### IBM SkillsBuild Data Analytics with AI Internship 2026

## Project Overview

EduPredict AI is a data analytics and machine learning project that analyzes student-related data and predicts final academic performance.

The project uses the UCI Student Performance dataset and applies exploratory data analysis, data visualization, Linear Regression and Random Forest Regression.

The system predicts the final grade (G3) using selected student features and converts the predicted grade into project-defined performance categories.

## Objectives

- Analyze student performance data.
- Perform data cleaning and exploratory data analysis.
- Visualize relationships between student features and final grades.
- Build machine learning models to predict final grades.
- Compare Linear Regression and Random Forest Regression.
- Generate performance categories from predicted grades.
- Export prediction and analysis results as CSV files.

## Dataset

The project uses the UCI Student Performance Mathematics dataset.

Important variables include:

- G1 – First-period grade
- G2 – Second-period grade
- G3 – Final grade
- studytime – Weekly study-time level
- failures – Number of previous failures
- absences – Number of school absences

## Machine Learning Features

The final prediction model uses:

- age
- studytime
- failures
- absences
- G1
- G2

## Models Used

1. Linear Regression
2. Random Forest Regression

## Evaluation Metrics

- MAE – Mean Absolute Error
- RMSE – Root Mean Squared Error
- R² Score

## Project Results

- Total Students: 395
- Average Actual Grade: 10.42
- Average Predicted Grade: 10.44
- Average Prediction Error: 0.52
- Best Model: Random Forest
- Random Forest R² Score: 0.854

## Predicted Performance Categories

The project uses these project-defined categories:

- Grade >= 15: High Performance
- Grade 10–14.99: Medium Performance
- Grade < 10: Low Performance

Predicted categories:

- Low Performance: 168 students
- Medium Performance: 165 students
- High Performance: 62 students

These categories are defined for this project and are not official academic standards.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Outputs

The project generates:

- student_performance_predictions.csv
- model_comparison.csv
- feature_importance.csv

## How to Run

Install the required libraries:

```bash
python -m pip install -r requirements.txt