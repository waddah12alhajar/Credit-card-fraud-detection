Fraudulent Credit Card Transactions Detection
Introduction: Credit card fraud is a serious concern for banks and customers worldwide. According to a report by Nilson, the global card fraud losses exceeded $27 billion in 2018, and the trend is rising. To mitigate the impact of fraud, it's crucial to develop effective fraud detection models. In this project, we aim to build a binary classification model to detect fraudulent credit card transactions using machine learning algorithms.

Dataset: The dataset used for this project is the Credit Card Fraud Detection dataset from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud). The dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset has 284,807 transactions, out of which 492 are fraudulent. The dataset contains 30 features, most of which are anonymized due to privacy concerns.

As the data is imbalanced, we will apply ٍSMOT technique to solve the imbalance so that the models will perform better.

Methods: The following machine learning algorithms will be experimented to build the fraud detection model:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. Neural Network
6. XGBoost Classifier

Hyperparameter tuning will be done where possible to adjust the hyperparameters to obtain the best possible results.

Evaluation Framework: The following evaluation metrics will be used to assess the quality of the algorithms:
1. Precision (important to minimize false positives)
2. Recall
3. F1 score
4. AUC-RO
