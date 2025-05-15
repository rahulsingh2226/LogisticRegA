Adult Income Prediction Using Logistic Regression
This project demonstrates a simple implementation of logistic regression to classify whether a person earns more than $50K per year based on census data (Adult dataset).

📂 Project Structure
Adult_LogisticReg.ipynb: Main Jupyter notebook containing the full workflow from data loading and preprocessing to model training and evaluation.

📊 Dataset
The dataset used is the UCI Adult Income Dataset which contains demographic and employment-related attributes to predict income. The target variable is whether the individual's income exceeds $50K/year.

⚙️ Features Used
The model uses a subset of features:

Bachelors

Adm-clerical

White

Male

Gov (derived from State-gov)

Country (derived from United-States)

🧪 Model
Model: LogisticRegression from sklearn

Balanced class weights to address class imbalance

📈 Evaluation Metrics
Confusion Matrix

Accuracy

F1 Score

Precision

Recall

📦 Dependencies
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn
