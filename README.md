# Sentiment-Py

A Python-based sentiment analysis project using natural language processing techniques.

## Overview

Sentiment-Py analyzes text data to determine the sentiment expressed within, whether it is positive, negative, or neutral. This can be applied to various domains like customer reviews, social media, and more.

## Features

- **Text Preprocessing:** Cleans and prepares text data for analysis.
- **Sentiment Classification:** Classifies text into positive, negative, or neutral sentiments.
- **Visualization:** Provides visual representations of sentiment distribution.

## Requirements

- Python 3.6+
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, nltk

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/noothispoorthi/sentiment-py.git
    cd sentiment-py
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook sentiment_spoorthi.ipynb
    ```

2. Follow the steps in the notebook to load data, preprocess text, train the model, and analyze sentiments.

## Example

```python
from sentiment_analysis import SentimentAnalyzer

analyzer = SentimentAnalyzer()
text = "I love this product! It's amazing."
result = analyzer.predict(text)
print(f"Sentiment: {result}")
