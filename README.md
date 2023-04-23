# Fake News Classification

This project aims to classify news articles as reliable or potentially unreliable using deep learning models and natural language processing techniques, specifically recurrent neural networks (RNN), long short-term memory (LSTM), and gated recurrent unit (GRU).

## Data Overview
The dataset used for this project is the Fake News dataset from Kaggle, which contains news articles with labels indicating their reliability. The dataset has two files: train.csv and test.csv. The former is used for training the models, while the latter is used for testing. The train.csv file has the following attributes:

- id: unique id for a news article
- title: the title of a news article
- author: author of the news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable (1) or reliable (0)

## Data Source
The dataset was sourced from Kaggle, and can be found at https://www.kaggle.com/competitions/fake-news/data.

## Methodology
The text data was pre-processed using NLP libraries such as TensorFlow and Keras. The pre-processed data was then used to train the RNN, LSTM, and GRU models. The models were evaluated using accuracy and F1-score metrics.

## Usage
To use the trained model for classification, the model can be deployed using Flask to provide a web interface for users to input and classify news articles.

## Results
The performance of the models was evaluated using accuracy and F1-score metrics. The best-performing model was the LSTM model, which achieved an accuracy of 92% and an F1-score of 0.92.

## Future Work
In the future, the model can be deployed using Flask to provide a web interface for users to input and classify news articles. Additionally, more data can be collected and added to the dataset to improve the accuracy and robustness of the models.
