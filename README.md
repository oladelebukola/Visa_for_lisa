# Welcome to Visa For Lisa
## Task
The Task was to use their pre-existing dataset to help Galaxy Bank improve its marketing conversion rates by allowing them to target and predict better which of their deposit clients are most likely to accept a loan offer from the bank

## Description
I used the following functions on the dataset provided:

def load_dataset(): It read the data from a file('Visa_For_Lisa_Loan_Modelling.csv')using a library-like pandas and returned the loaded DataFrame.

def clean_dataset(VisaForLisa_dataframe):t is used to perform data cleaning and preprocessing operations on the dataset.
by taking the original DataFrame as input (VisaForLisa_dataframe), performs the cleaning operations, and returns the cleaned DataFrame.

def print_histograms(dataset):It took the cleaned dataset as input and plots histograms for each variable/attribute providing insights into the distribution and range of values for each variable.

def compute_correlations_matrix(VisaForLisa_dataframe):It computed the pairwise correlation coefficients as interpreted('Personal Loan', 'Experience' and 'Income') between all pairs of variables and returns the correlation matrix thereby displays the relationships between variables, indicating how they are related or dependent on each other.

def print_scatter_matrix(VisaForLisa_dataframe):It took the cleaned dataset (VisaForLisa_dataframe) as input and plots scatter plots between pairs of variables thereby visualizing the relationships and patterns between pairs of variables.

def logistic_regression_model(data):It took the cleaned dataset (data) as input, split it into features and the target variable, and perform train-test splitting,fitting a logistic regression model on the training data, make predictions on the test data, and calculates evaluation metrics such as accuracy, precision, recall, and F1 score. Finally, it printed the evaluation metrics and returned the trained logistic regression model.

Presentation slides can be seen in: https://1drv.ms/p/s!AnlZ6SsnWAMOjT1mnKvoKVDRXCLV?e=87haGM

## Installation
There was no need for any installation as it can be run on local machine using Jupyter notebook and other necessary dependencies

## Usage
The code was run on a jupyter notebook whose http address can be gotten by running this in the terminal:
jupyter notebook
then the jupyter address can be followed after inserting 'web' and the password 'qwasar' inputed
Run 'pip install -U scikit-learn' on the terminal

### The Core Team
Bukola Veronica Oladele(veronica_b)

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>