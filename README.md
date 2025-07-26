# Week-4
I-Powered Issue Prioritization Using Breast Cancer Dataset

This project shows how Artificial Intelligence can be used to predict issue priority (High/Low) using real-world medical data. It uses the breast cancer dataset from scikit-learn to simulate a priority system, where malignant cases are labeled as "high priority" and benign cases as "low priority." The model is built using Random Forest Classifier and runs in Google Colab.

Project Structure:

notebook.ipynb: Google Colab notebook with the full code

README.txt: Project overview (this file)

Objectives:

Load and prepare data using sklearn

Train a Random Forest model to classify priority

Evaluate the model using accuracy and F1-score

Apply AI to a resource allocation scenario in a healthcare context

Dataset Overview:

Source: Breast Cancer Dataset from scikit-learn

Total records: 569 samples

Features: 30 numeric attributes per patient

Diagnosis classes:

Malignant → High priority

Benign → Low priority

Technologies Used:

Python

Google Colab

Pandas

Scikit-learn (Random Forest, model evaluation)

Model Workflow:

Load breast cancer data from sklearn.datasets

Map diagnosis into "high" and "low" priority categories

Split the dataset into training (80%) and testing (20%)

Train a Random Forest Classifier on the training set

Use the trained model to predict priorities on test data

Evaluate predictions using accuracy and F1-score

Model Results:

Accuracy: ~95.6%

F1 Score for high-priority predictions: ~94.9%

How to Run:

Open notebook.ipynb in Google Colab

Run all cells top-to-bottom

Dataset is built-in — no need to upload files

Ethical Considerations:

It is important to detect and reduce biases in the dataset, especially when applying models in sensitive areas like healthcare. Tools like IBM AI Fairness 360 can be used to test fairness and improve model accountability.

Future Improvements:

Add feature importance plots to explain model decisions

Use SHAP or LIME to make AI predictions explainable

Create a user interface with Streamlit or Flask to test predictions live

Author:

Anderson Onkangi
AI Enthusiast | Healthcare Innovator | Student Leader
Kenya

