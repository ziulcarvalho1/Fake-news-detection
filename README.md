# Fake-news-detection
 Using NLP to detect fake news
The objective

The general objective of the project is to design and implement an AI application 
capable of identify if an article is fake or not. 
The approach 

Although the general objective seems clear enough, we have to define our approach regards the problem. Here we have our first Decision. Many  combinations of approaches can be used:
•	Initially we deployed AI techniques to compare the title of the article with the body text identifying if they correlated to each other.
•	Secondly we identify the subject of the text and try to guess the chance that it be a fake news (For instance news about Hollywood have a much better chance to be fake than science news –Sentiment analysis)
•	Thirdly we identify the tone of the article – Angry, scary, condescending – Fake news usually try to induce strong feeling in people.
We are going to use a combination of these factors. 
