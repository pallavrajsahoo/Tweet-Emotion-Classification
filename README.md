# Tweet-Emotion-Classification
Tweet Emotion Classification using Natural Language Processing (RNN) in TensorFlow


Here, I have created a Recurrent Neural Network and train edit on a tweet emotion dataset to learn to recognize emotions in tweets. The dataset has thousands of tweets each classified in one of 6 emotions. Below is how the data ser looks like
```diff
{'test': Dataset(features: {'text': Value(dtype='string', id=None), 'label': Value(dtype='string', id=None)}, num_rows: 2000),
 'train': Dataset(features: {'text': Value(dtype='string', id=None), 'label': Value(dtype='string', id=None)}, num_rows: 16000),
 'validation': Dataset(features: {'text': Value(dtype='string', id=None), 'label': Value(dtype='string', id=None)}, num_rows: 2000)}
 ```
 
 Here is the list of 6 classes or emotions.
 ```diff
 {'anger', 'fear', 'joy', 'love', 'sadness', 'surprise'}
 ```
 
This is a multi class classification problem in the Natural Language Processing domain. 
I have used TensorFlow and used Keras api as my machine learning framework.


This is my Kaggle link for the project. Feel free to check it out.

https://www.kaggle.com/code/pallavrajsahoo/tweet-emotion-classification-using-rnn
