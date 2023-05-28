# Sentiment-Analysis | NLP

## Goal 
To create a robust machine learning model utilizing natural language processing (NLP) that analyzes user-uploaded reviews to determine their sentiment (positive or negative) and generates appropriate responses accordingly.

## Dataset
I employed reviews sourced from a restaurant website to train my model and was pleasantly surprised to discover its remarkable performance, even when handling reviews unrelated to the restaurant domain.

## Overview 
* I leveraged NLTK to conduct preprocessing, eliminating stopwords (words that do not contribute to sentiment analysis) while also removing non-alphabetic symbols and numbers. Subsequently, all text was transformed to lowercase for consistency.

* Utilizing a bag-of-words model, I extracted the top 1530 most frequent words and employed them to visualize a wide range of reviews. Subsequently, I converted the extracted words into a numpy array, facilitating future training.

* I trained the Naive Bayes model by feeding it the reviews as a numpy array. Following the training phase, I utilized the model for prediction, incorporating conditional statements to generate responses based on the analysis conducted.

## Installation


1. Clone the project:
```
$ git clone https://github.com/rrajsinghhada/Sentiment-Analysis | NLP
$ cd Sentiment-Analysis | NLP
```
2. Install the required dependencies by running the following command:
```
pip install requirements.txt
```
3. Run Sentiment-Analysis.ipynb

 ## Result
 Cunfusion matrics

| 55 | 42 |
| -- | -- |
| 12 | 91 |

