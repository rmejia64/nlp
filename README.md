# Natural Language Processing Sentiment Analysis

This project demonstrates sentiment analysis using various vectorization techniques and machine learning models. It aims to classify text data into positive or negative sentiment categories based on the content of the text.

## Table of Contents

[Background](#Background)<br/>
[Installation](#Installation)<br/>
[Usage](#Usage)<br/>
[Contributing](#Contributing)<br/>
[License](#Liscense)<br/>

### Background

Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. It has various applications, including social media monitoring, customer feedback analysis, and product reviews sentiment analysis.

### Installation

To run this project, you'll need Python installed on your machine. You can install the required dependencies using pip:

```
pip install -r requirements.txt
```

This will install all necessary packages, including NumPy, pandas, scikit-learn, tqdm, NLTK.
Please note: Spellchecker must be installed seperately: 

```
pip install pyspellchecker
```

### Usage

Download GloVe Embeddings: Download the GloVe word embeddings file (glove.840B.300d.txt) from the GloVe website or other sources and place it in the datasets directory.
Run the Script: Execute the main script (sentiment_analysis.py) to perform sentiment analysis. This script loads the GloVe embeddings, preprocesses the text data, trains a logistic regression model, evaluates the model's performance, and allows for interactive sentiment analysis input.
pre-flagged datasets: https://www.kaggle.com/datasets/marklvl/sentiment-labelled-sentences-data-set

```
python [sentiment_analysis].py
```

replace [sentiment_analysis] with filename of model you wish to run.
Interpret the Results: After running the script, the model's performance metrics (accuracy, F1 score, precision, and recall) will be displayed. Additionally, you can input your own text for sentiment analysis and observe the predicted sentiment (positive or negative).

### Contributing

Contributions are welcome! If you have any ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
