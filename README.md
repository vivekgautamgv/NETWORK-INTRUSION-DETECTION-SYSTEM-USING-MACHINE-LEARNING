Network Intrusion Detection System Using Machine Learning
A machine learning-based system for detecting network intrusions using the NSL-KDD dataset.
Features

Binary classification of network traffic as normal or intrusive
Implementation of multiple ML algorithms
Data preprocessing and feature engineering
Performance evaluation metrics

Dependencies

Python 3.x
scikit-learn
pandas
numpy
matplotlib
seaborn

Dataset
Uses NSL-KDD dataset, an improved version of KDD Cup'99 dataset, containing:

41 features
Binary classification (normal/attack)
Preprocessed network traffic data

Implementation

Data Preprocessing

Feature scaling
Label encoding
Train-test split


Models Used

Random Forest
Support Vector Machine
K-Nearest Neighbors
Decision Tree



Performance Metrics

Accuracy
Precision
Recall
F1-Score
Confusion Matrix

Usage

Clone the repository
Install dependencies: pip install -r requirements.txt
Run NIDS.ipynb using Jupyter Notebook

Results
The system achieves high accuracy in detecting network intrusions while maintaining low false-positive rates.
Contributing
Feel free to submit issues and pull requests.
License
MIT License
Author
Vivek Gautam
