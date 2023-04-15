# Topic Modeling with NMF

This repository contains a Python code to perform topic modeling on movie reviews using Non-negative Matrix Factorization (NMF) and Natural Language Processing (NLP) techniques.

## Installation

To run this code, you need to install the following libraries:
- numpy
- pandas
- scikit-learn
- nltk

```python
pip install numpy pandas scikit-learn nltk
```

## Usage

The code reads movie reviews from a CSV file and performs the following tasks:
- Cleans the text data by removing stopwords and lemmatizing the words.
- Vectorizes the cleaned text using TfidfVectorizer.
- Performs NMF on the vectorized text to extract 10 topics.

You can modify the number of topics, maximum features, and minimum document frequency in TfidfVectorizer and NMF parameters according to your requirements.

## Dataset

The dataset used in this code is 'reviews.csv', which contains movie reviews. You can provide your own dataset in CSV format to analyze the topics based on your domain.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
