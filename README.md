 Human Activity Recognition (HAR) using Smartphone Sensors
 ------------------------------------------------------------
📌 Project Overview

This project focuses on Human Activity Recognition (HAR) using smartphone sensor data.
By analyzing accelerometer and gyroscope signals, the system predicts the physical activity performed by a person while carrying a smartphone.

The goal is to demonstrate a complete machine learning pipeline, from data understanding and visualization to model training and evaluation.



Activities Recognized
----------------------

The model classifies the following six human activities:

-Walking

-Walking Upstairs

-Walking Downstairs

-Sitting

-Standing

-Laying

📊 Dataset
-----------
Source: UCI Machine Learning Repository – Human Activity Recognition Dataset

Description:
Sensor signals (accelerometer & gyroscope) collected from smartphones worn on the waist.

Features: 561 engineered features in both time and frequency domains.

Sampling Rate: 50 Hz


🔗 Dataset link:
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

The dataset is not included in this repository due to size limitations.


Technologies & Tools
---------------------

-Python

-NumPy & Pandas

-Scikit-learn

-Matplotlib & Seaborn

-Jupyter Notebook

 
Methodology
------------

-Exploratory Data Analysis (EDA)

-Signal behavior comparison across activities

-Time-domain vs frequency-domain feature analysis

-Model Training

-Random Forest Classifier

-Support Vector Machine (SVM) with RBF kernel

-Evaluation

-Accuracy score

-Confusion matrix analysis

-Model comparison


Results
-----------
-Model	Accuracy
Random Forest	92.6%
Support Vector Machine (SVM)	~93–95%

Observations:
SVM achieved slightly higher accuracy due to better handling of high-dimensional feature space.
Sitting and Standing activities were the most frequently confused classes, which is expected due to similar static sensor patterns.


Key Insights
-----------------

-Frequency-domain features (FFT-based) significantly improve classification performance.

-Scaling is critical for distance-based models such as SVM.

-There is a trade-off between model interpretability (Random Forest) and accuracy (SVM).


Future Improvements
----------------------

-Hyperparameter tuning with GridSearchCV

-Dimensionality reduction (PCA)

-Deep learning approach (CNN / LSTM)

-Real-time activity recognition from live sensor data

Author
--------
-Sude Naz Çimen
-Computer Engineering Student
-Interested in Data Science, Machine Learning.

