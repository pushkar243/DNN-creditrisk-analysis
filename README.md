Objective: Implement one of the papers chosen in  using Python TensorFlow Keras or Pytorch Libraries.
We have implemented code 10171259_credit_risk_prediction_based_on_DL_and_SMOTE
Journal used for the implementation
Journal title: Proposal of a model for credit risk prediction based on deep learning methods and SMOTE techniques for imbalanced dataset

Authors:

Adaleta Gicić, Engineering Faculty, University of Sarajevo, Bosnia and Herzegovina
Dženana Ðonko, Engineering Faculty, University of Sarajevo, Bosnia and Herzegovina
Journal Name: The architecture of the deep learning models discussed in the paper involves Stacked LSTM and Stacked BiLSTM networks:

Number of Layers: Both Stacked LSTM and Stacked BiLSTM architectures consist of three hidden layers.

Year: 2021

Table of Contents
1.Introduction
2.Data Acquisition
3.Data Preparation
4.Deep Neural Network Architecture
4.1 Design the architecture
4.2 DNN Report
Training the Model
Testing the Model
Result Analysis
7.1 Accuracy and Loss
7.2 Confusion Matrix
7.3 Performance Study Metrics
Conclusion
Introduction
This repository contains the implementation of a credit risk prediction model using deep learning techniques, specifically Stacked LSTM, and SMOTE for handling imbalanced datasets. The model's architecture is inspired by the work discussed in the referenced journal.

Data Acquisition
For this project, the German Credit Data was used, obtained from UCI Machine Learning Repository. Two datasets, 'german.data' and 'german.data-numeric,' were utilized and processed for further analysis.

Data Preparation
The data underwent preprocessing steps, including handling missing values, splitting into features and target variables, and standardizing the data. Additionally, the dataset was split into training and testing sets.

Deep Neural Network Architecture
4.1 Design the architecture
The deep learning model utilizes Stacked LSTM layers to capture temporal dependencies in the data. The architecture includes three LSTM layers with varying units and a final Dense layer for binary classification.

4.2 DNN Report
Number of Layers: 4 (3 LSTM layers and 1 Dense layer)
Number of Units:
LSTM layer 1: 60 units
LSTM layer 2: 80 units
LSTM layer 3: 120 units
Dense layer: 1 unit (output layer)
Total Trainable Parameters: 108,481
Training the Model
The model was trained using the processed data with appropriate configurations, including the Adam optimizer, binary crossentropy loss, and accuracy metrics.

Testing the Model
The trained model was evaluated on the testing dataset to assess its performance.
Result Analysis
7.1 Accuracy and Loss
The training and validation accuracy and loss histories were visualized to observe the model's learning progress over epochs.
7.2 Confusion Matrix
A confusion matrix was generated to visually represent the model's performance on the testing dataset.
7.3 Performance Study Metrics
Performance metrics, including precision, recall, F1 score, and accuracy, were reported for further analysis.

Conclusion
In conclusion, this project implements a deep learning model for credit risk prediction based on the referenced journal's architecture. The model demonstrates its ability to handle imbalanced datasets using SMOTE and achieve satisfactory accuracy on the testing dataset.
