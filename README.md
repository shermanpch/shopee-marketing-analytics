# Shopee Code League - Marketing Analytics

## Background
The aim of this project is to build a model that can predict whether a user opens the emails sent by Shopee.

Sending emails is one of the marketing channels Shopee uses to reach out to our users. Being able to predict whether a user opens an email allows Shopee to forecast and evaluate the performance of future marketing campaigns before launch. This is because when a user opens an email, the probability of the user knowing the campaign increases and this in turn increases the probability of the user making a checkout during the campaign period. Therefore, with the predicted open rates, Shopee can better develop, strategize and implement future marketing campaigns.

## Task
Data related to marketing emails (Electronic Direct Mail) that were sent to Shopee users over a certain period are provided. It contains information about:

- User-specific information
- Email nature
- Users’ engagement on the platform
- User’s reaction to the email, including whether users opened the email
- Based on the data provided, you must predict whether each user will open an email sent to him/her.

## Evaluation Metric
Submissions are evaluated on the Matthews correlation coefficient (MCC) between the predicted and the observed response. The MCC is given by:
<br>
<br>
<p align="center"><img src="https://latex.codecogs.com/svg.latex?MCC&space;=&space;\frac{(TP*TN)-(FP*FN)}{\sqrt{(TP&plus;FP)(TP&plus;FN)(TN&plus;FP)(TN&plus;FN)}}" title="MCC = \frac{(TP*TN)-(FP*FN)}{\sqrt{(TP+FP)(TP+FN)(TN+FP)(TN+FN)}}" width="600"></p>where TP is the number of true positives, TN the number of true negatives, FP the number of false positives, and FN the number of false negatives.

## Results
|Public Leaderboard|Private Leaderboard|
|:---|:---|
|0.54168|0.52693|

## Reference
**Jupyter Notebook**
<br>
https://github.com/shermanpch/shopee-sentiment-analysis/blob/master/shopee-marketing-analytics.ipynb

**Shopee Code League - Marketing Analytics**
<br>
https://www.kaggle.com/c/open-shopee-code-league-marketing-analytics
