# Surgery Operating Length Prediction: A Patients Finder Tool

Hi, welcome to my Git repository which contains the information for the **Surgery Operating Length Prediction** project! :)

This project applies machine learning techniques to optimize surgery scheduling by predicting surgery durations. Developed for *Monash Health*, this project incorporates a backend model to estimate surgery times accurately and a front-end tool for efficient scheduling. The tool aims to improve theater utilization and patient flow while minimizing operating costs in medical institution.

## Repository Structure

-   **Patient_Finder_Tool Code repo**: contains the back-end modeling code for this project (the data folder in this repo is empty, as the data is confidential)
-   **Patient Finder Tool - UI Mock up.pbix**: contains the demo front-end tool for this project
-   **Presentation**: contains the presentation slides for this project
-   **Report**: contains the report for this project

## Project Overview

This project, conducted during an internship with Monash Health—Victoria’s largest public health service—aims to enhance surgery scheduling efficiency through predictive modeling. By estimating surgery durations, this tool supports patient prioritization from the waiting list to improve operating theater utilization and reduce idle time. Although the model’s accuracy still allows room for improvement, it offers valuable insights for managing resources and addressing operational delays, aligning with Monash Health's commitment to accessible, high-quality healthcare.

### Methodology

The project leverages multiple machine learning models, each selected for its strengths in handling complex healthcare data:

1.  **Random Forest:** A robust ensemble model that captures non-linear relationships in surgery duration data and handles high-dimensional feature sets.
2.  **Ridge and Lasso Regression:** Regularized regression models used for feature selection and to prevent overfitting, especially for highly correlated features.
3.  **Gradient Boosting Machine (GBM):** A powerful boosting algorithm used to improve accuracy by sequentially correcting errors.

### Model Tuning and Cross-Validation

Hyperparameter tuning was applied to each model using a cross-validated grid search to optimize performance on the surgery dataset. Cross-validation ensures that the model's predictive accuracy generalizes to unseen data.

### Front-End Tool Integration

In addition to the backend model, a front-end tool was developed to serve as a demo interface for Monash Health staff. This interface, built with simulated data, allows easy prioritization of patients, facilitating better scheduling decisions in real time.

### Results

After extensive testing, the Random Forest model was selected as the best fit for this project, providing reasonable and consistent predictions of surgery durations. This model strikes a balance between accuracy and interpretability, making it suitable for supporting scheduling decisions within Monash Health's operational environment.
