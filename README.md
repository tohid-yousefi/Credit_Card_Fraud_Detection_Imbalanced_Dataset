# Credit Card Fraud Detection: Imbalanced Dataset
In this section, we will credit card fraud detection on an imbalanced dataset.

<hr />

📌 **Imbalanced dataset** is seen in classification problems and occurs when the class distributions are not close to each other. The problem is that the majority class dominates the minority class. The model created is close to the majority class, which causes poor classification of the minority class.

📌 When we encounter imbalanced data sets, there are various methods we can apply to make accurate observations and maintain balance:

* Choosing the Suitable Metrics
  * Precision
  * Recall
  * F1-score
  * ROC Curve
  * AUC
* Resampling
  * oversampling
    * Random Oversampling
    * SMOTE Oversampling
  * undersampling
    * Random Undersampling
    * NearMiss Undersampling
    * Undersampling (Tomek links)
    * Undersampling (Cluster Centroids)
* collect more data
* Creating a model that can learn equally from minority and majority classes by using the "class_weight" parameter in classification models
* Looking at the performances of other models, not just one model
* Applying a different approach and performing Anomaly detection or Change detection

# Dataset Story

📌 The data set consists of transactions made with credit cards in Europe in September 2013 and labeling these transactions as 0 if not 1 if they are fraudulent. For privacy reasons, there is not much background information and other variables, except for the "Time","Amount" variable, have been converted with PCA(Principal component analysis).

* Time: the second between the first operation and each operation

* Amount: cost

Click this <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">link</a> to download the dataset.
