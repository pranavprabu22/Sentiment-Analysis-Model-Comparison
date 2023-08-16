# Sentiment Analysis Model Comparison
This repository contains 4 different sentiment analysis models and tests their efficiency based on key metrics to draw a conclusion on what is the most optimal common sentiment analysis model.

### Step 1: Obtaining the Dataset
The dataset used for all models in this repository is the IMDB movie review dataset in the '''datasets''' package

### Step 2: Pre-Processing of data
##### REMOVING PUNCTUATIONS
Using regular expression(regex), remove punctuation, hashtags and @-mentions from each movie review.</br>

##### TOKENIZATION
In order to use textual data for predictive modeling, the text must be parsed to remove certain words – this process is called tokenization.</br>

##### STEMMING
Stemming is the process of reducing inflected words to their word stem, base, or root form—generally a written word form.</br>

##### LEMMATIZATION
Lemmatization in linguistics is the process of grouping together the inflected forms of a word so they can be analyzed as a single item, identified by the word's lemma, or dictionary form.</br>

### Step 3: Fitting and training the model
##### Implemented Algorithms
###### NAIVE BAYES CLASSIFIER
The Naive Bayes Classifier is a model that assigns class labels to problem instances, represented as vectors of feature values, where the class labels are drawn from some finite set.
###### SENTIMENT INTENSITY ANALYZER
The Sentiment Intensity Analyzer is a rule-based sentiment analyzer in which the terms are generally labeled as per their semantic orientation as either positive or negative.
###### DistilBERT
DistilBERT is a small, fast, cheap, and light Transformer model based on the BERT architecture. Knowledge distillation is performed during the pre-training phase to reduce the size of a BERT model by 40%. To leverage the inductive biases learned by larger models during pre-training, the authors introduce a triple loss combining language modeling, distillation, and cosine-distance losses.
###### LOGISTIC REGRESSION
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).
###### SUPPORT VECTOR MACHINE (SVM)
In machine learning, support-vector machines are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis.

### Conclusion
Among all other techniques used, and taking into account the f1 score for each model, the SVM model has performed best.

### Step 4: Model prediction and result comparison

### Future Improvements for Sentiment Analysis
* Multilingual sentiment analysis.
* Can take emoticons and pictures attached into account to predict better for the sentiment.
* Apart from the positive and negative categories, the model could be developed to learn to classify tweets that are satirical or sarcastic, and either remove them from the results for positive and negative sentiment or properly distribute them.
