
# Depression Prediction

Social media platforms like Facebook, Twitter, and Instagram have permanently changed our world. People are more connected than ever and have developed a kind of online character. Social networking undoubtedly has some amazing perks, but there are also unquestionable drawbacks. Recent research has suggested a link between heavy social media use and elevated depression. The goal of the current study is to apply machine learning approaches to identify Twitter users who may be sad based on both their network behaviour and tweets. Using data gleaned from a person's network activities and tweets, we trained and tested classifiers to determine whether a user is depressed or not. The findings indicated that the accuracy and F-measure scores in identifying depressed users increased with the number of features included. A data-driven, predictive strategy is used in this technique to identify depression or other mental diseases early on. The exploration of the traits and their impact on determining the degree of depression is the primary contribution of this work.

# Libraries Used

NLTK

Re

Numpy

Pandas 

Matplotlib

Seaborn

Wordcloud

Tensorflow 

PIL (Python Imaging Library)

scipy

Sklearn

Keras

# Dataset 

Amazon Review Full Score Dataset

Version 3, Updated 09/09/2015

# Data Collection Information

The Amazon reviews dataset consists of reviews from amazon. The data span a period of 18 years, including ~35 million reviews up to March 2013. Reviews include product and user information, ratings, and a plaintext review. For more information, please refer to the following paper: J. McAuley and J. Leskovec. Hidden factors and hidden topics: understanding rating dimensions with review text. RecSys, 2013. The Amazon reviews full score dataset is constructed by Xiang Zhang (xiang.zhang@nyu.edu) from the above dataset. It is used as a text classification benchmark in the following paper: Xiang Zhang, Junbo Zhao, Yann LeCun. Character-level Convolutional Networks for Text Classification. Advances in Neural Information Processing Systems 28 (NIPS 2015).


# Data Description

The Amazon reviews full score dataset is constructed by randomly taking 600,000 training samples and 130,000 testing samples for each review score from 1 to 5. In total there are 3,000,000 trainig samples and 650,000 testing samples.

The files train.csv and test.csv contain all the training samples as comma-sparated values. There are 3 columns in them, corresponding to class index (1 to 5), review title and review text. The review title and text are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). New lines are escaped by a backslash followed with an "n" character, that is "\n".

# Libraries Used 

