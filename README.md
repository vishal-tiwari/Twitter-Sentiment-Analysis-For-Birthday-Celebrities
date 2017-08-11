# Twitter Sentiment Analysis For Birthday Celebrities
## Problem Statement
IMDB provides a list of celebrities born on the current date. Below is the link: http://m.imdb.com/feature/bornondate

Get the list of these celebrities from this webpage using web scraping (the ones that are displayed i.e top 10). You have to extract the below information:

  1. Name of the celebrity
  2. Celebrity Image
  3. Profession
  4. Best Work
  
Once you have this list, run a sentiment analysis on twitter for each celebrity and finally the output should be in the below format

  1. Name of the celebrity:
  2. Celebrity Image:
  3. Profession:
  4. Best Work:
  5. Overall Sentiment on Twitter: Positive, Negative or Neutral
  
## Tools and Packages Used

  •	Version: Python 2.7 

  •	Tweepy : Tweepy is an open-sourced, hosted on GitHub, and enables Python to communicate with the Twitter platform and use its API.

  •	Codecs : The codecs module provides stream and file interfaces for transcoding data in your program. In this project I use the   module     for storing the tweets as Unicode text. Here's the documentation.

  •	String (punctuation) : To strip the tweets of all punctuations.

  •	BeautifulSoup : Beautiful Soup provides a few simple methods and Pythonic idioms for navigating, searching, and modifying a parse tree     using Python parsers like lxml and html5lib. It automatically converts incoming documents to Unicode and outgoing documents to UTF-8.     Here's the documentation.

  •	Selenium : The webdriver kit emulates a web-browser (I chose Chrome) and executes the JS scripts to load the dynamic content.
  
## Important

  You can get your key and token from given link: https://apps.twitter.com after registring your app and webdriver from link: https://sites.google.com/a/chromium.org/chromedriver/downloads
  
