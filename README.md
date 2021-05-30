# sentiment-analysis-using-nlp-python
 Identify the emotions of the reviews.using NLP
Sentiment Analysis is the most common text classification tool that analyses an incoming message and tells whether the underlying sentiment is positive, negative our neutral.
In this Sentiment Analysis is performed on Reviews given by customers in https://www.trustpilot.com/review/olacabs.com website for the ola review

Technical Aspect:
I have selected Reviews given by customers in https://www.trustpilot.com/review/olacabs.com website for the ola review

This project is divided into three parts:
1-main.py 
In this reading text file,splitting,text into words.
 Check if the word in the final word list is also present in emotion.txt
#  - open the emotion file.
#  - Loop through each line and clear it.
#  - Extract the word and emotion using split.

# 2) If word is present -> Add the emotion to emotion_list.
# 3) Finally count each emotion in the emotion list.
# Plotting the emotions on the graph.
2-main_sentence.py
# Using word_tokenize because it's faster than split().
# Removing Stop Words.
# Lemmatization - From plural to single + Base form of a word (example better-> good)
