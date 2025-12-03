This project aims to build a classification model to predict the fetal health status (fetal_health) — Normal, Suspect, or Pathologic — based on clinical data from Cardiotocography (CTG) examinations.
Key Methods and Analysis:
Comprehensive Data Preprocessing: The data (fetal_health.csv) was thoroughly cleaned, including handling missing values, dropping duplicate data, and managing outliers. The data was then normalized to ensure consistent feature ranges.
Data Balancing & Feature Selection: To address class imbalance in the target variable, the SMOTE technique was used. Additionally, feature selection was performed using Mutual Information (SelectKBest) to optimize model input.
Model Comparison: The performance of four main classification algorithms was compared: Naive Bayes, Decision Tree, Random Forest, and SVM.
Optimization: The Decision Tree model was deeply optimized using RandomizedSearchCV to find the best hyperparameter combination.

Key Results:
Following comparison and optimization, the Random Forest model demonstrated the highest performance with an Accuracy of 0.937 (93.7%), making it the most reliable model for predicting fetal health status.
