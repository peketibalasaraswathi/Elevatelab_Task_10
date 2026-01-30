# Elevatelab_Task_10

This project implements Handwritten Digit Classification using the K-Nearest Neighbors (KNN) algorithm on the Sklearn Digits dataset.
The objective is to understand distance-based classification, the importance of feature scaling, and K value tuning.

# Dataset

Name: Sklearn Digits Dataset

Source: sklearn.datasets.load_digits()

Images: 8×8 grayscale digit images (0–9)

Total Samples: 1797

Each image is flattened into 64 numerical features.



# Tools & Technologies Used

Python

Google Colab

Scikit-learn

NumPy

Matplotlib


# Project Workflow

Loaded the digits dataset and verified feature & label shapes

Visualized sample digit images to confirm labels

Split dataset into training and testing sets

Applied StandardScaler for feature scaling

Trained KNN model with K = 3

Evaluated model accuracy

Tested multiple K values (3, 5, 7, 9)

Plotted Accuracy vs K graph to find optimal K

Generated Confusion Matrix to analyze misclassifications

Displayed test images with predicted labels


# Results & Outputs
Accuracy vs K Plot

  Shows how model accuracy changes with different K values.

Confusion Matrix

  Visual representation of correct and incorrect predictions for each digit.

Sample Predictions

  Displayed test images with predicted digit labels.

  All output images are saved in the outputs/ folder.


# output


# Key Learnings

Understanding KNN as a distance-based algorithm

Importance of feature scaling in KNN

Effect of K value on model performance

Model evaluation using accuracy and confusion matrix


# Final Outcome

This task helped in building a strong foundation in distance-based machine learning models and understanding hyperparameter tuning using KNN.
