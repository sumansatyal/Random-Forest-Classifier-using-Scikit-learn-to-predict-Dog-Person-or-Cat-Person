# Random-Forest-Classifier-using-Scikit-learn-to-predict-Dog-lover-vs-Cat-lover

Predicting if a person likes Dogs or Cats

Overview
This repository contains a Jupyter Notebook demonstrating the implementation of a Random Forest Classifier using scikit-learn. The notebook explores the process of building, evaluating, and using the classifier to predict whether a customer is likely to be a 'dog-person' or a 'cat-person' based on survey data.

Survey Questions
-	Do you like walking?
-	Do you like running?
-	What is your favorite color?
-	How many miles do you walk in a day
A data file that contains answers to above questions are given in the .csv file.

Contents
- `random_forest_classifier.ipynb`: Jupyter Notebook containing the code and explanation of the Random Forest Classifier implementation.
- `cat-or-dog.csv`: Sample dataset used in the notebook for training and testing the classifier.

Usage
To run the notebook locally, follow these steps:
1. Clone the repository to your local machine.
2. Install Jupyter Notebook if not already installed: `pip install notebook`
3. Navigate to the directory containing the notebook.
4. Run `jupyter notebook` command to start the Jupyter server.
5. Access the notebook in your web browser and execute the cells to observe the implementation.

Usage on AWS SageMaker
To use this notebook on AWS SageMaker, follow these steps:
1. Log in to the AWS console.
2. Navigate to the AWS SageMaker page.
3. Create a Notebook instance
4. Open Instance, Open Jupyter

Load and Prepare the Data
1. Load the survey data from `cat-or-dog.csv`, located beside the notebook.
2. View the data. Look at both the raw data and statistics for the data.
3. Change the column data types so the model can understand them.
4. Split the data into training and testing sets. Use 80% of the data for training.

Train the Random Forest Model
1. Create a Random Forest Classifier model using scikit-learn.
2. Train the model using the training data.
Evaluate the Model
1. Generate predictions for the testing dataset.
2. View the confusion matrix for the predictions.
3. Calculate the sensitivity and specificity.
4. Plot the ROC curve.
5. Calculate the area under the curve.

Make a prediction for Yourself
1. Create a survey response for yourself.
2. Have the model predict if you prefer cats or dogs.

Dependencies
The following Python libraries are required to run the notebook:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

Key Features of scikit-learn:
- Simple and efficient tools for data mining and data analysis.
- Accessible to everybody and reusable in various contexts.
- Built on NumPy, SciPy, and matplotlib.
- Open source and commercially usable under the BSD license.

Scikit-learn is designed to be user-friendly, with a consistent API and extensive documentation. It's widely used in academia and industry for tasks ranging from simple data analysis to complex machine learning models.
![image](https://github.com/sumansatyal/Random-Forest-Classifier-using-Scikit-learn-to-predict-Dog-lover-vs-Cat-lover/assets/60155963/deb55d29-86bb-4239-a6a4-6d292c33b904)
