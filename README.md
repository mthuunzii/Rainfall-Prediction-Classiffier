**Rainfall Prediction Classifier - Final Project**

Project Overview
This project focuses on building a machine learning classifier to predict rainfall in the Melbourne area using historical weather data from the Australian Bureau of Meteorology. The goal is to explore feature engineering, build classifier pipelines, optimize models using grid search cross-validation, and evaluate model performance.

**Dataset**
The dataset contains daily weather observations from 2008 to 2017, including:

Temperature metrics (MinTemp, MaxTemp, Temp9am, Temp3pm)

Rainfall measurements

Wind direction and speed

Humidity and pressure readings

Cloud cover and sunshine hours

Location and seasonal information

Key Features
Feature Engineering: Created a 'Season' feature from dates and dropped redundant columns

**Data Preprocessing:**

Handled missing values by dropping rows

Scaled numerical features

One-hot encoded categorical variables

**Model Building:**

Implemented RandomForestClassifier and LogisticRegression

Used GridSearchCV for hyperparameter tuning

**Evaluation:**

Classification reports

Confusion matrices

Feature importance analysis

Project Structure
Data loading and exploration

Feature engineering and preprocessing

Model building and optimization

Performance evaluation

Comparison of different classifiers

**Key Findings**
The dataset showed class imbalance with more "No Rain" days than "Rain" days

RandomForestClassifier achieved 84% accuracy on test data

Feature importance analysis revealed humidity and pressure as top predictors

LogisticRegression showed comparable performance with different characteristics

**How to Run**
Install required packages: numpy, pandas, matplotlib, scikit-learn, seaborn

Execute the notebook cells sequentially

The notebook will:

Load and preprocess data

Build and evaluate models

Display performance metrics and visualizations

Dependencies
Python 3.x

Libraries listed in requirements.txt
