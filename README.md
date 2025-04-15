# Customer-Purchase-Prediction-Using-Machine-Learning

This project focuses on predicting customer purchasing behavior using both classical ML algorithms and deep learning models. The dataset includes customer details such as gender, age, estimated salary, visit behaviour, and user id.

# Dataset
 [datasets/Customer_Behaviour.csv](datasets/Customer_Behaviour.csv) – Raw customer behavior data used for training and evaluation.


# Requirements

 Install dependencies using

 pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# How to Use

 * Open the Jupyter Notebook: jupyter notebook CustomerPrediction.ipynb

 * Run the notebook to explore data insights.


# Features & Methods
## 1. Data Preprocessing & Cleaning

 * Dropped rows with missing values.

 * Filled missing values with the median.

 * Ensured data consistency for analysis.


## 2. Feature Correlation Analysis

![Count Of Gender](images/Countofgender.png)

![Count Of purchased](images/countofpurchased.png)

![Correlation Heatmap](images/Correlation.png)

![Scatter Plot of Features](images/scatterplot.png)

![3D PlotBased on Age, Estimated Salary, Gender and Purchased](images/newplot.png)


## 3. Machine Learning Model

* Logistic Regression

                         Classification Report
                        precision    recall  f1-score   support

      No Purchased=0       0.92      0.97      0.94        58
      Purchased=1          0.89      0.77      0.83        22
      accuracy                                 0.91        80
      macro avg            0.91      0.87      0.89        80
      weighted avg         0.91      0.91      0.91        80
      Jaccard Score: 0.71


![Confusion Matrix](images/Confusionmatrix.png)

![Model](images/model.png)

![ROC curve](images/Roc.png)

![Visualization Of Prediction](images/visualize.png)


* Deep Learning (TensorFlow)

                          Classification Report
                        precision    recall  f1-score   support

      No Purchased=0       0.98      0.95      0.96        58
      Purchased=1          0.88      0.95      0.91        22
      accuracy                                 0.95        80
      macro avg            0.93      0.95      0.94        80
      weighted avg         0.95      0.95      0.95        80


![Model Sequential](images/param.png)

![ROC CURVE](images/Roccurve.png)

![ROC curve](images/Confusion.png)



