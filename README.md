# World University Ranking Prediction

A data science project to predict university rankings based on the 2026 QS World University Rankings dataset using machine learning techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to predict the overall scores of universities in the 2026 QS World University Rankings using machine learning models. The dataset includes various metrics such as academic reputation, employer reputation, and sustainability scores. The project employs data preprocessing, exploratory data analysis (EDA), and machine learning techniques to build predictive models.

## Dataset
The dataset used is the **2026 QS World University Rankings** (`2026 QS World University Rankings.csv`). It contains information about universities worldwide, including:
- **2026 Rank**: Current ranking of the university.
- **Institution Name**: Name of the university.
- **Country/Territory**: Location of the university.
- **Region**: Geographical region.
- **Size, Focus, Research, Status**: Categorical features describing the university.
- **AR SCORE, ER SCORE, FSR SCORE, CPF SCORE, IFR SCORE, ISR SCORE, ISD SCORE, IRN SCORE, EO SCORE, SUS SCORE**: Numerical scores for various ranking metrics.
- **Overall SCORE**: The target variable for prediction.

## Features
- **Data Cleaning**: Handling missing values, converting categorical variables, and removing unnecessary rank columns.
- **Exploratory Data Analysis (EDA)**: Correlation heatmap to identify relationships between features.
- **Machine Learning Models**:
  - Linear Regression
  - Random Forest Regressor
- **Evaluation Metrics**: Root Mean Squared Error (RMSE) and R² score.
