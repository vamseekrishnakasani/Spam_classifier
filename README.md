# Spam Email Classification using Logistic Regression (PyTorch)

## Overview
This project implements **Logistic Regression** using **PyTorch** to classify emails as **Spam or Legitimate**.  
The model is trained on the **Spambase dataset** from the **UCI Machine Learning Repository**, which contains **57 numerical features** extracted from emails.  

The goal is to build a classifier that predicts whether an email is spam or not based on its content.

--------------------------------------------------------------------------------------------------

## Installation & Setup
Before running the project, make sure you have **Python 3.x** installed.  

To install the required dependencies, run the following command:

```bash
pip install numpy pandas torch scikit-learn matplotlib
```

This will install the necessary libraries:  
- **NumPy** → For handling numerical data.  
- **Pandas** → For working with datasets.  
- **PyTorch** → For building and training the model.  
- **Scikit-Learn** → For data preprocessing and model comparison.  
- **Matplotlib** → For visualizations.  

--------------------------------------------------------------------------------------------------

## How to Run the Code
### Prepare the Dataset
- The dataset is **automatically loaded** from the **UCI Machine Learning Repository**, so no manual download is required.
- The script fetches the dataset from the UCI Machine Learning Repository.

--------------------------------------------------------------------------------------------------

### Run the Main Script
Navigate to the folder where the script exists, then run the main script to train and evaluate the model. All dependencies are installed before running it.
```bash
python spam_detection_classifier.py
```

### This script will:
- Load and preprocess the dataset.
- Train a Logistic Regression model using PyTorch.
- Evaluate the model on the test dataset.
- Compare performance with Scikit-Learn's Logistic Regression.
- Generate plots showing model accuracy, loss trends, and decision boundaries.

--------------------------------------------------------------------------------------------------

## Expected Outputs
### Once the script runs successfully, it will display:
- Training loss and accuracy for each epoch.
- Final test accuracy of the model.
- Generated plots:
  - Loss vs. Epochs
  - Test Accuracy over Epochs
  - Spam vs. Legitimate Classification Decision Boundary
  - Effect of Learning Rate on Performance
