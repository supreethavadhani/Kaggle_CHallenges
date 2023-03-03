# Titanic: Machine Learning from Disaster

This is my solution for the Titanic: Machine Learning from Disaster competition on Kaggle. The goal of this competition is to predict whether or not a passenger survived the sinking of the Titanic, based on various information such as their age, gender, and ticket class.

## Data
The data for this competition is available on the Kaggle website. It consists of two CSV files: train.csv and test.csv. The train.csv file contains information about a subset of the passengers, along with a binary indicator of whether or not they survived. The test.csv file contains similar information about a different subset of the passengers, but without the survival information.

## Approach
To solve this problem, I used a variety of machine learning algorithms, including decision trees, random forests, and bagging algorithms. I also performed extensive feature engineering, including imputing missing values, creating new features based on existing ones, standardization, normalization and encoding categorical variables.

To evaluate the performance of my models, I used cross-validation and the Kaggle leaderboard, which provides a score based on the accuracy of predictions on the test set. I also used performance metrics, classification_report,accuracy_score,confusion_matrix to evalute my model. 

## Results
After experimenting with various models and features, my best-performing model achieved an accuracy of 75.6% on the Kaggle leaderboard, which placed me in the top 30% of competitors.

## Repository Contents
This repository contains a Jupyter notebooks which has data preprocessing, feature engineering, and model training, as well as for exploratory data analysis and model evaluation.

data: contains the input data files (train.csv and test.csv) and the output submission file (submission.csv)
notebooks: contains Jupyter notebooks for exploratory data analysis and model evaluation
src: contains Python scripts for data preprocessing, feature engineering, and model training

## Usage
To reproduce my results, follow these steps:

Clone this repository to your local machine
Install the required Python packages (pip install -r requirements.txt)
Run the Jupyter notebooks in the notebooks directory to explore the data and evaluate the models
Run the Python scripts in the src directory to preprocess the data, engineer features, and train the models
Use the trained models to generate predictions on the test set and submit them to Kaggle using the submission.csv file in the data directory