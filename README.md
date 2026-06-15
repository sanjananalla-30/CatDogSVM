Cat vs Dog Image Classification using SVM

📌 Project Overview

This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs using the Kaggle Dogs vs Cats dataset. The images are preprocessed using OpenCV, converted into feature vectors, and then classified using Scikit-Learn's SVM algorithm.

🎯 Objective

Build a machine learning model capable of distinguishing between cat and dog images with good accuracy.

📂 Dataset

Dataset: Dogs vs Cats Dataset (Kaggle)

🛠️ Technologies Used

Python

Jupyter Notebook

OpenCV

NumPy

Matplotlib

Scikit-Learn

📋 Project Workflow

1. Data Collection

Downloaded the Dogs vs Cats dataset from Kaggle.

Extracted images from the dataset.

2. Data Preprocessing

Loaded images using OpenCV.

Resized images to 64×64 pixels.

Flattened image arrays into feature vectors.

Assigned labels:

Cat → 0

Dog → 1

3. Train-Test Split

Split dataset into:

80% Training Data

20% Testing Data

4. Model Training

Trained a Support Vector Machine (SVM) classifier using Scikit-Learn.

Algorithm Used:

- Support Vector Machine (SVM)

- Kernel: Linear


5. Model Evaluation

Evaluated model performance using:

Accuracy Score

Classification Report

📊 Results

The SVM model successfully classifies cat and dog images after preprocessing and feature extraction.

Example Output:

Accuracy: 85%

(Accuracy may vary depending on dataset size and preprocessing.)

🔮 Future Improvements

Use larger datasets.

Apply feature extraction techniques such as HOG.

Perform hyperparameter tuning.

Compare SVM with CNN and Deep Learning models.

Deploy the model as a web application.

👨‍💻 Author

N.Sanjana
