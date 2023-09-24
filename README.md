
# Text Classification on Consumer Complaint Dataset

This project involves performing text classification on a consumer complaint dataset to categorize complaints into four predefined categories: Credit reporting, repair, or other, Debt collection, Consumer Loan, and Mortgage. The goal is to build a machine learning model that can automatically classify consumer complaints into these categories based on the text content of the complaints.

# Dataset

1. Dataset source: [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)

2. Description: The dataset contains consumer complaints related to various financial products and services. It includes text descriptions of complaints and their associated categories.

# Steps to Follow
# 1. Explanatory Data Analysis and Feature Engineering
(i) Load the dataset and explore its structure and contents.

(ii) Check for missing values and handle them if necessary.

(iii) Analyze the distribution of complaints across different categories.

(iv)Perform feature engineering if needed, like creating new features based on the complaint text.

# 2. Text Pre-Processing

Clean and preprocess the text data by:

Removing special characters, numbers, and symbols.

Converting text to lowercase.

Removing stop words.

Lemmatizing or stemming words.

# 3. Selection of Multi-Classification Model

Choose a suitable machine learning or deep learning model for multi-class classification(used RNN here).

Split the dataset into training and testing sets.

Train the selected model on the training data.

# 4. Comparison of Model Performance

Evaluate the model's performance using appropriate metrics (e.g., accuracy, F1-score).
Experiment with different models and hyperparameters to find the best-performing one.

# 5. Prediction

Deploy the trained model for making predictions on new consumer complaints.
Provide a user-friendly interface or API for users to input complaints and receive category predictions.

# 6. Results

Summarize the performance of the trained models.
Provide insights into the challenges and potential areas for improvement.




