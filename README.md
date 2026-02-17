# Palmer-Penguins-Analysis

📌# Project Overview

This project presents an exploratory data analysis (EDA) and machine learning classification of the Palmer Penguins dataset.
The goal of the project is to analyze physical characteristics of penguins and build a model that predicts the species based on measurable features.

The analysis includes data cleaning, visualization, correlation analysis, and a supervised classification model.

📊# Dataset Description

The dataset contains measurements of penguins from three species:

Adelie

Chinstrap

Gentoo

Main Features:

bill_length_mm

bill_depth_mm

flipper_length_mm

body_mass_g

sex

island

year

🧹# Data Cleaning

Removed unnecessary index column.

Handled missing numeric values using median imputation.

Filled missing categorical values (sex) using mode within species groups.

Verified dataset integrity after preprocessing.

📈# Exploratory Data Analysis (EDA)

The analysis revealed several important relationships:

A strong positive correlation between flipper length and body mass, indicating that larger penguins tend to have longer flippers.

A moderate positive correlation between bill length and body size measurements.

A moderate negative correlation between bill depth and overall body size, suggesting structural differences between species.

The year variable showed no meaningful correlation with physical measurements.

Visualization techniques used:

Count plots

Scatter plots

Box plots

Correlation heatmap

🤖# Machine Learning Model

A Random Forest Classifier was trained to predict penguin species using numeric features.

Model Features:

Bill length

Bill depth

Flipper length

Body mass

Results:

Very high overall accuracy.

Perfect classification for Chinstrap and Gentoo species.

Minor misclassification within Adelie, likely due to overlapping physical characteristics.

The confusion matrix demonstrates strong model performance with minimal classification errors.

🛠# Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

🎯# Key Takeaways

Physical body measurements are highly predictive of penguin species.

Flipper length and body mass are the strongest correlated features.

The dataset is well-structured and suitable for both EDA and classification tasks.

Random Forest performs exceptionally well on this dataset.

🚀# Future Improvements

Feature engineering (e.g., ratio-based features).

Hyperparameter tuning for improved robustness.

Cross-validation for stronger evaluation.

Deployment as an interactive dashboard (Streamlit / Power BI).

👤 Author

Raz Ben-Yehuda
B.Sc. Industrial Engineering & Management
Specialization in Information Systems & Business Analytics
