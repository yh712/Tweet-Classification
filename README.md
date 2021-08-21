# Tweet-Classification
**Author:** Yuhsiang (Sean) Hong, Yitao Liu

## Description
Our goal is to build machine learning models to classify tweets with hashtag Python against tweets with hashtag NBA. For our strategy, first, we collect as many as tweets as possible because we might remove some tweets after data cleaning. Second, we organize and clean tweet data. Third, we set TF-IDF and word embeddings as inputs for each model. Next, we run Naive Bayes, Logistic Regression and simple neural networks with one hidden layer and 50 units using scikit-learn as our baseline models. After that, we implement complex neural networks such as DNN and RNN using TensorFlow. Lastly, we compare results of using different models and draw our conclusion.

## Data Collection
Tweets were collected by `tweepy` with Python. Tweets were created from November 13th to November 20th. We originally acquired 43810 Python tweets and 21499 NBA tweets. However, there were many tweets that were identical such as advertisement tweets. These kinds of tweets were usually created in a short period of time with the same context. Therefore we dropped these duplicate tweets and the total number of remaining Python tweets was 10133 and the total number of remaining NBA tweets was 15251.

## Package
All the following Python packages are used in this project:
`pandas`, `numpy`, `re`, `csv`, `json`, `string`, `random`, `sklearn`, `matplotlib`, `seaborn`, `nltk`, `gensim`, `tensorflow`.
