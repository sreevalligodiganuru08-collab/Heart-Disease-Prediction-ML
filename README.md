# Heart-Disease-Prediction-ML
# Heart Disease Prediction using Machine Learning

## Project Overview

This project aims to predict the presence of heart disease using patient medical data and machine learning algorithms. The project demonstrates the complete machine learning workflow including data preprocessing, feature selection, model training, evaluation, and comparison of multiple classification models.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

## Dataset Information

The dataset contains medical attributes of patients such as:

* Age
* Sex
* Chest Pain Type
* Blood Pressure
* Cholesterol
* ECG Results
* Maximum Heart Rate
* Exercise Angina
* ST Depression
* Thallium Test Results

Target Variable:

* Heart Disease

  * Presence = 1
  * Absence = 0

## Machine Learning Workflow

### 1. Data Preprocessing

* Dataset inspection
* Missing value verification
* Duplicate record verification
* Target label encoding

### 2. Feature Selection

* Input Features (X)
* Target Variable (y)

### 3. Train-Test Split

* 80% Training Data
* 20% Testing Data

### 4. Model Training

The following machine learning algorithms were implemented:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

### 5. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Heatmap Visualization

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 92.59%   |
| Random Forest       | 79.63%   |
| KNN                 | 64.81%   |

## Best Model

Logistic Regression achieved the highest accuracy of 92.59% and was selected as the best-performing model for heart disease prediction.

## Key Insights

* Logistic Regression outperformed both KNN and Random Forest.
* The dataset was clean with no missing values or duplicate records.
* Machine learning models can effectively predict heart disease using patient clinical data.
* Logistic Regression generalized better on this dataset due to its size and feature characteristics.

## Conclusion

This project successfully developed and compared multiple machine learning models for heart disease prediction. The results demonstrate how machine learning can assist healthcare professionals in identifying patients at risk of heart disease using clinical information.

## Author

Sreevalli Godiganuru
