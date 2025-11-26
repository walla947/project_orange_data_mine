### Breast Cancer Classification – Orange Data Mining Project ###

This project applies a complete data science workflow using Orange Data Mining to classify breast cancer tumors as benign or malignant.
The workflow includes data exploration, preprocessing, model training and evaluation using multiple machine learning algorithms.

## 🔍 Data Exploration ##

Data exploration was performed using Orange visualization widgets such as:

Correlation Heat Map – to analyze relationships between numerical features

Dataset inspection – to verify target column, data types and missing values

## 🧹 Data Preparation ##

The dataset was preprocessed with:

Select Columns (feature and target selection)

Impute (handling missing values)

Continuize (normalizing numerical variables for distance-based models)

These steps ensured that all machine learning algorithms received data in the correct format.

## 🤖 Machine Learning Models ##

Three supervised classification algorithms were tested:

Logistic Regression

k-Nearest Neighbors (kNN)

Decision Tree

All models were evaluated using Cross Validation via the Test & Score widget.

## 📊 Results ## 

Metrics collected:

Accuracy (CA)

AUC

F1-Score

Precision

Recall

MCC

Best performance was obtained with Logistic Regression and kNN, while the Decision Tree performed slightly worse but remained interpretable.
