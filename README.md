
# Game of Throne research for Marketing and Product Ideas

## Purpose
The Client is in promotional item industry specialize in printing, customization and survivors. As recently Game of Thone has its finale, customer wants to know if there is business opportunity for Thanksgiving.
We are trying to find the market trend in order to develop correct item and show them to correct people by explore reddit’s subreddit to see what people like and talk about.  
## How to use this repo
There are two notebooks in this project, first notebook is about scraping and EDA. In order to do that, you would need a reddit account at https://www.reddit.com/register/, after that, you would gain API access by going to https://www.reddit.com/prefs/apps  
The second notebook focus on using different model and evaluation to find the best model, in order to find the best words for marketing and product information

## Executive Summary
During the model comparison, I compaired 7 models and find the best model, using that model to compute the top words, top words without cheatwords, two-word phrases, three word phrases and four word phrases. 
## Results:
Based on model testing, the best model to fit the data and problem is TIFDF with Logistic regression model. Model score on test data is 0.91, with ROC AUC of 0.97. 
![word_count](./assets/plots/modelandscore.png)
![word_count](./assets/plots/ROCAUC.png)
# Specificity: 0.9197
# Specificity: 0.9033
## Conclusions:
Here is the list of words that are important to reddit users in these two subreddit:
![image.png](./assets/plots/final.png)

# Recommendation:
- Buy Ad words for the one word and two worded phrases on Reddit to promote the website
- Use these words to create promotional items(theme related item) such as T-shirt, stickers and toys. 

