# Breast-Cancer-Detection

Classifies Tumors As Benign (Non-Cancerous) Or Malignant (Cancerous) using Stochastic Gradient Descent

Data source: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/breast-cancer-wisconsin.data

Relevant Information:

Samples arrive periodically as Dr. Wolberg reports his clinical cases.
The database therefore reflects this chronological grouping of the data.

## This Model uses 9 features:

1. Clump Thickness
2. Uniformity of Cell Size
3. Uniformity of Cell Shape
4. Marginal Adhesion
5. Single Epithelial Cell Size
6. Bare Nuclei
7. Bland Chromatin
8. Normal Nucleoli
9. Mitoses
11. Class(Y variable): (2 for benign, 4 for malignant)

Class distribution:
 
Benign: 458 (65.5%)
Malignant: 241 (34.5%)

Note: The machine learning model is save in the "model" file, and the scaling technique used to standardize the data, is saved in the "scalar" file.