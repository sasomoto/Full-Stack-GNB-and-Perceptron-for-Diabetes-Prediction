#-Full-Stack-GNB-and-Perceptron-for-Diabetes-Prediction
Includes custom Perceptron implementation and flask backend as well as html front end


Objective
Train and evaluate two models—Naive Bayes and Perceptron—to classify diabetes types based on input features (age, blood sugar level, insulin level, and BMI). Compare the models' performance using metrics such as accuracy, precision, recall, and F1-score. Save both models for deployment in a Flask-based web application for real-time predictions.

Task Outline
Step 1: Import Libraries
Import necessary libraries including GaussianNB, Perceptron, and pickle for model training, evaluation, and saving.
Step 2: Data Preprocessing
Load Dataset: Load the dataset and separate it into features (X) and target (y).
Train-Test Split: Split data into training and test sets (80-20 split).
Feature Scaling: Apply scaling (StandardScaler or MinMaxScaler) if needed to improve model performance.
Step 3: Train the Naive Bayes Model
Initialize and train the Naive Bayes model on the training data.
Use the trained model to make predictions on the test data.
Step 4: Train the Perceptron Model
Train a Perceptron model on the training data using either a library or custom implementation.
Generate predictions on the test data.
Step 5: Model Evaluation
Evaluate both models using accuracy, precision, recall, and F1-score.
Analyze the results, discussing each model’s strengths and weaknesses.
Step 6: Save the Models with Pickle
Save both trained models as .pkl files using the pickle library for future deployment.
Step 7: Set Up Flask Backend
Set up a Flask application to serve the models and create an endpoint (/predict) for real-time predictions.
Enable CORS to allow cross-origin requests from the frontend.
Step 8: Create the Frontend
Develop a simple HTML + JavaScript interface with input fields for age, blood sugar, insulin, and BMI.
Use JavaScript (fetch API) to send user inputs to the backend and display the predicted diabetes type on the page.
Step 9: Implement K-Fold Cross-Validation
Apply k-fold cross-validation to each model for a more robust performance evaluation.
Step 10: Compare and Analyze Results
Compare both models’ evaluation metrics across cross-validation results and highlight findings.
