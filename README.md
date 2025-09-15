# Handwritten-Digits-Recognition-with-SVC-and-Decision-Trees
This project explores two popular machine learning models, Support Vector Classifier (SVC) and Decision Tree Classifier, to recognize handwritten digits. The goal is to compare the performance of both models using a well-known dataset.

# Project Overview
The code uses the load_digits dataset from Scikit-learn, which contains a collection of 8x8 pixel images of handwritten digits from 0 to 9. The project includes the following steps:
Data Loading and Visualization: The dataset is loaded and a few sample images are displayed to provide a visual understanding of the data.
Data Splitting: The data is split into training and testing sets to evaluate model performance on unseen data.

Model Training and Comparison: Two models are trained:
SVC (Support Vector Classifier): A powerful model for classification, here with an rbf kernel for non-linear decision boundaries.
Decision Tree: A simple, yet effective, tree-based model.
Performance Evaluation: The models are evaluated using accuracy score, classification reports, and confusion matrices to assess how well they predict the correct digits. The results are also saved to a result.txt file for easy reference.
Confusion Matrix Visualization: The confusion matrices for both models are plotted to visually identify which digits are being misclassified.

# Key Findings
The analysis shows that the SVC model significantly outperforms the Decision Tree model on this dataset. This is primarily because the SVC with an RBF kernel is better at finding complex, non-linear patterns in the data compared to the Decision Tree, which may overfit or fail to capture all the subtleties of the images.
