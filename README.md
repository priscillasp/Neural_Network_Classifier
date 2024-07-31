# Dual-Output Neural Network for Employee Attrition Prediction
## Overview
This repository contains a Jupyter notebook (attrition.ipynb), which outlines the process of building and evaluating a neural network model designed to predict employee attrition and department classification based on a set of employee characteristics.

## Repository Contents
attrition.ipynb: A comprehensive notebook that walks through the following stages:
- Preprocessing: Data is imported, inspected, and prepared for modeling. This includes selecting features, splitting data into training and testing sets, and applying transformations such as scaling and encoding.
    - The features selected for this model: Age, Distance From Home, Education, Job Satisfaction, Over Time, Percent Salary Hike, Job Level, Years At Company, Years Since Last Promotion, Hourly Rate and Environment Satisfaction
- Model Building: Constructs a neural network with two branches in a non-sequential configuration, each tailored to predict one of the two target variables: department and attrition.
- Model Evaluation: After training, the model is evaluated on the testing set to determine its accuracy and performance in predicting both targets.

## Key Features
- **Data Preparation**: Detailed preprocessing steps ensure the data is optimally formatted for neural network input.
- **Dual-Output Model**: The model architecture allows simultaneous predictions for two different outcomes, demonstrating a practical application of multi-output neural networks.
- **Model Evaluation**: Evaluation metrics provide insights into the model's performance, highlighting its effectiveness and areas for improvement.

