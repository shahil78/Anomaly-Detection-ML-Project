AnomaData: Automated Anomaly Detection for Predictive Maintenance

Project Overview:
AnomaData is an anomaly detection system designed to support industries with predictive maintenance. By identifying anomalies in machine data, AnomaData helps predict machine breakdowns before they happen. This proactive approach helps industries reduce downtime, minimize risks, and gain actionable insights from their equipment data.

Objective:
The main goal of this project is to detect machine breakdowns by identifying anomalies in the data. The dataset consists of 18,000+ rows, where each row represents a set of machine readings. The label (y) indicates whether an anomaly is present (1 = anomaly, 0 = no anomaly).

Project Structure:

*) Data Preparation:
- Missing Value Treatment
- Duplicate Row Check
- Exploratory Data Analysis (EDA)
- Outlier Detection and Treatment
- Data Balancing using SMOTE and Random Undersampling
- Data Scaling

*) Modeling:
- Random Forest Classifier: Provides feature importance and performs well with large datasets.
- K-Nearest Neighbors (KNN): Effective in identifying anomalies by comparing neighbors.
- Naive Bayes: Useful for probabilistic classification, good for high-dimensional data.
- Logistic Regression: Offers clear decision boundaries and interpretable results.

*) Hyperparameter Tuning:
- Used GridSearchCV to optimize the models and improve performance.
  
*) Evaluation Metrics:
- Accuracy, Confusion Matrix, ROC AUC Score, Log Loss, and others.

Models Used:
- Random Forest: Best for capturing feature importance and non-linear relationships in the data.
- K-Nearest Neighbors: Effective in identifying anomalies by comparing new data points to its neighbors.
- Naive Bayes: A simple probabilistic classifier, useful for making predictions quickly.
- Logistic Regression: Useful for interpreting relationships between the predictors and the outcome.

Performance: 

Each model was evaluated using multiple metrics:
- Random Forest: Accuracy improved to 100% after hyperparameter tuning.
- KNN: Accuracy of 98% after tuning.
- Naive Bayes: Accuracy of 79% after tuning.
- Logistic Regression: Accuracy of 89% with good precision and recall.

Conclusion:

AnomaData is a powerful tool for predictive maintenance, leveraging multiple machine learning models to detect anomalies in real-time. This project can be customized to fit different industrial applications to predict and prevent costly machine breakdowns.
