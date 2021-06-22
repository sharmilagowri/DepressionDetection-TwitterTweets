# DepressionDetection-TwitterTweets

Detecting depressed twitter tweets using NLP and Deep Learning Models. Utilized Sentiment Analysis to classify tweets related to Depression. Considered Logistic Regression as a baseline model. Build TFIDF and BOW models from NLP. Also built models using LSTM, CNN and GLoVE.

Scraped real time tweets from twitter API using Tweepy Library in python. Using a unique key and token, an authorized connection to the API is established and tweets with ‘depressive’ tags are scraped. Tweet user Location, hour of tweet, local time, retweets and using naïve bayes classifier – captured the sentiment of live tweets

We used GLoVE word embeddings pretrained model and Google's pretrained word2vec model
