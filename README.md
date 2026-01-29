Project Overview
This project demonstrates the fundamental process of evaluating a Machine Learning model using the Heart Disease Dataset. The focus is on splitting data to prevent overfitting and using multiple metrics to interpret the model's reliability in a medical context.

Tools Used:
Python: Core programming language.
Scikit-learn: For data splitting (train_test_split), model training (LogisticRegression), and performance metrics.
Pandas: For data manipulation and loading.

Implementation Workflow
1. Data Splitting
Action: Divided the dataset into Training (80%) and Testing (20%) sets.
Purpose: The training set is used to teach the model patterns, while the testing set provides an unbiased evaluation of how the model performs on unseen data.
2. Model Training
Algorithm: Implemented Logistic Regression, a standard classification algorithm used to predict binary outcomes (e.g., Heart Disease: Yes/No).
Prediction: Generated predictions on the test set to compare against actual known values.
3. Performance Metrics
To fully understand the model's effectiveness, the following metrics were calculated:
Accuracy: Percentage of total correct predictions.
Precision: The ratio of true positive predictions to the total predicted positives.
Recall: The ability of the model to find all actual positive cases (highly critical in healthcare).
4. Confusion Matrix
Analysis: A confusion matrix was generated to visualize the model's performance by showing True Positives, True Negatives, False Positives, and False Negatives.
