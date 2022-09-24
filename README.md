# RoBERTa-for-Textual-Data-Classification-problems
This project is for the task of twitter emotion analysis by RoBERTa

Different people express different sentiments using different words. This phenomenon is particularly evident on online social platforms. Further, as psychological studies reveal, sentiment and emotions vary over a broad spectrum and are characterized by taxonomies.
In this project, you are required to predict the sentiment of a given content on Twitter. In a simplified manner, the sentiment provided in this task is either positive or negative.

Dataset

The dataset consists in a collection of tweets in tabular format. Each record is characterized by several attributes. The following is a short description for each of them.

• ids: a numerical identifier of the tweet;

• date: the publication date;

• flag: the query used to collect the tweet;

• user: the username of the original poster;

• text: the text of the tweet.

The sentiment of the tweet is reported on the feature named sentiment and is equal to 1 for the Positive class and 0 for the Negative one.

Our submissions will be evaluated through F1 score (Macro)

After preprocessing, we select SVM as our baseline (F1 score = 0.770)

We then use RoBERTa to improve the results(F1 score = 0.871).
