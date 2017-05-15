# Tweet_Sentiment_Analysis
Classifying tweets into three classes based on the sentiments each one of the tweet holds

Given a test dataset (2012 Presidential Elections tweets for Obama and Romney) that contains 8 classes, I filtered the tweets to fall
broadly into 3 classes. Then preprocessed the new data set wherein I substituted acronyms for actual phrases, substitute emoticons for 
what the intend to express, used snowball stemmer and a customized the stopword list. Following that, I trained my classifier which is a
SVM.SVC classifier. Executing it on the test data gave me an accuracy of close to 59% for Obama and 62% for Romney.  
