# IMDb Rating Prediction Project

Welcome to the IMDb Rating Prediction project repository! This project focuses on predicting IMDb movie ratings using machine learning techniques. Below, you'll find an overview of the project, instructions for usage, and other relevant information.

## Project Overview

In this project, we aim to predict IMDb movie ratings by leveraging machine learning algorithms. We follow a step-by-step process, which includes data preprocessing, feature engineering, model building, and evaluation. The primary technologies and libraries used in this project include:

- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## Code Structure

Here's a brief overview of the key sections of the code:

1. **Importing Libraries**: In the initial code snippet, we import the necessary Python libraries for data analysis and machine learning.

2. **Data Loading**: We load the training and test datasets (`train_data.csv` and `test_data_with_inputs.csv`) using Pandas.

3. **Data Exploration**: We start by exploring the training dataset, checking its shape, information, and some basic statistics. Additionally, we create a pair plot to visualize relationships between certain features.

4. **Feature Engineering**: In this section, we perform feature engineering, which includes encoding categorical variables (Language, Country, Content Rating) into dummy variables.

5. **Data Cleaning**: We drop irrelevant or redundant columns from both the training and test datasets to prepare them for modeling.

6. **Data Splitting**: The training data is split into training and testing sets to evaluate model performance.

7. **Data Scaling**: We standardize the features to ensure consistent scaling for modeling.

8. **Model Building**: We implement an ensemble model using the Voting Regressor, combining Gradient Boosting, Random Forest, and Linear Regression models.

9. **Model Evaluation**: We evaluate the model's performance using metrics like R-squared and Root Mean Squared Error (RMSE) on the test dataset.

10. **Prediction on Test Data**: Finally, we use the trained model to predict IMDb scores for the test dataset and save the results in an output file.

## Usage

To use this code for IMDb rating prediction:

1. Clone this GitHub repository to your local machine.

   ```bash
   git clone https://github.com/srujayreddyv/ImdbRatingPrediction.git
   cd ImdbRatingPrediction
