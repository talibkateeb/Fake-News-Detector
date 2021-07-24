# Fake News Detector

## Overview

For this project I applied a supervised learning classification model to a dataset of news articles to predict Real vs. Fake news. This fake news is usually spread through online media, and is done to serve political, economic, and nationalist ideologies by viralizing propoganda. Using a TfidfVectorizer and a PassiveAggressiveClassifier, I am able to combat this fake news.

[TfidfVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html):

* Term Frequency (TF): This defines the number of times a word shows up in a document. A high term frequency means that the term appears at a higher frequency than other terms. 

* Inverse Document Frequency (IDF): This measures how significant a term is by comparing it across many other documents to determine if it is irrelevant or not. 

* The TfidfVectorizer will convert the collection of raw documents into a matrix made up of TF-IDF features that I will use for the model.

[PassiveAggressiceClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.PassiveAggressiveClassifier.html): 

* [Passive Aggressive Algorithms are a family of online learning algorithms (for both classification and regression) proposed by Crammer at al. The idea is very simple and their performance has been proofed to be superior to many other alternative methods like Online Perceptron and MIRA](https://www.bonaccorso.eu/2017/10/06/ml-algorithms-addendum-passive-aggressive-algorithms/)

---

## Results

Accuracy Score: 94%

Confusion Matrix:
 * 612 True Positives
 * 582 True Negatives
 * 34 False Positives
 * 39 False Negatives

 Classification Report:

![](https://github.com/talibkateeb/Fake-News-Detector/blob/main/classification_report.png)


---

## Technologies

* Python

* SciKit-Learn

* Pandas

* Numpy

---

## License

[Click Here to View](https://github.com/talibkateeb/Fake-News-Detector/blob/main/LICENSE)