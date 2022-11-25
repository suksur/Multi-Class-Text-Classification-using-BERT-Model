# Multi-Class-Text-Classification-using-BERT-Model

BERT is an open-source ML framework for Natural Language Processing.
BERT stands for Bidirectional Encoder Representations and is a pre-trained model from
Google known for producing state-of-the-art results in a wide variety of NLP tasks.


## Aim
To perform multiclass text classification on the dataset using the pre-trained BERT
model.
## Data Description
The dataset contains more than two million customer complaints about consumer
financial products. Amongst the various available columns, we have a column that
contains the actual text of the complaint and one column containing the product for
which the customer is raising the complaint.
## Tech Stack
➔ Language: Python
➔ Libraries: pandas, torch, nltk, numpy, pickle, re, tqdm, sklearn, transformers
## Approach
1.Installing the necessary packages through the pip command
2.Importing the required libraries
3.Defining configuration file paths
4.Process Text data
▪ Read the CSV file and drop the null values
▪ Replace duplicate labels
▪ Encode the label column and save the encoder and encoded labels
5. Data Preprocessing
▪ Conversion to lower case
▪ Punctuation removal
▪ Digits removal
▪ Remove more than one consecutive instance of 'x'
▪ Additional spaces removal
▪ Tokenize the text
▪ Save the tokens
6. Model Building
▪ Create BERT model
▪ Create a function for the PyTorch dataset
▪ Function to train the model
▪ Function to test the model
7. Train BERT model
▪ Load the files
▪ Split data into train, test, and validation
▪ Create PyTorch datasets
▪ Create data loaders
▪ Create model object
▪ Define loss function and optimizer
▪ Move the model to GPU if available
