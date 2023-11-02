# datantics
Random data analysis projects: all project folders are under the "/code" directory.

## Projects
- [#1: Topic Modeling](#topic-modeling-on-ufc-news-articles)
- [#2: Sentiment Analysis & Keyword Extraction](#sentiment-analysis--keyword-extraction-of-user-reviews-on-steam)
- [#3: Convolutional Neural Network](#convolutional-neural-network-for-image-classification)
- [#4: Random Forest vs. Multilayer Perceptron for binary classification](#ufc-fight-statistics-analysis-and-prediction)
- [#5: Word2Vec Algorithm: Continuous Bag of Words](#continuous-bag-of-words-producing-distributed-representation-of-words)

## Topic Modeling on UFC news articles
Ultimate Fighting Championship (UFC)'s news articles are scraped from the official website and are analyzed uner the Latent Dirichlet Allocation (LDA) algorithm to identify hidden topics within the articles and their respective common terms. Furthermore, one can also see how well it conforms with UFC's own article categorization. The source code is under the folder "/code/ufc". More information on the findings can be read [here](https://medium.com/@pradhanang.sanjiv/topic-modeling-on-ufc-news-articles-with-latent-dirichlet-allocation-lda-73ea30e4516a).

## Sentiment Analysis & Keyword Extraction of user reviews on Steam
[Steam](https://store.steampowered.com/) is a video game digital distribution service. User reviews are gathered from for game products for sentiment analysis and keyword extraction. An attempt to gauge the effectiveness of Support Vector Machine for this sort of classification and to identify the most important words in the reviews is made. The source code is under the folder "/code/steam". More information on the findings can be read [here](https://medium.com/@pradhanang.sanjiv/sentiment-analysis-via-support-vector-machine-of-keyword-extraction-from-user-reviews-on-steam-70c76b52c253).

## Convolutional Neural Network for Image classification
Here we take an image dataset from [Kaggle](https://www.kaggle.com/datasets/smeschke/four-shapes?resource=download&select=process_data.py) and build a CNN to classify the images by one of the four different shapes that the image displays. The folder in the repo for the source code is "/code/shapes". More on the project can be read [here](https://medium.com/@pradhanang.sanjiv/convolutional-neural-network-for-image-classification-via-pytorch-b0e221ae194).

## UFC fight statistics analysis and prediction
UFC fight data scraped from [UFC Stats](http://ufcstats.com/), are used to train Random Forest Classifier and Multilayer Perceptron. We attempt to predict the result of the fight and whether the fight ends within 2 and a half rounds or not. More on the project is available [here](https://medium.com/@pradhanang.sanjiv/analysis-of-ufc-fight-statistics-and-models-for-fight-results-and-over-under-prediction-ade7080224bf).

## Continuous Bag of Words: Producing Distributed Representation of Words
On a toy [dataset](https://huggingface.co/datasets/breadlicker45/youtube-comments) of youtube comments, a simple Word2Vec model is applied. Particularly, the Continuous bag of words model is applied to get the word vectors/embeddings. The model can be used for Skip-gram as well by a simple change in the data format.