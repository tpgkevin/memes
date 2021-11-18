# **Lifetime of Memes**
This project was motivated by the commonly held belief that memes used to stay more popular than they currently do, or in other words, that memes are dying faster. I created this project to get a more concrete answer as to the nature of the lifetime of memes. To do so, I created a database of meme names by web-scraping them from knowyourmemes.com website, acquired their daily popularity using google trend's unofficial api (pytrends), and finally determined how long they lasted in the spotlight by computing their half-life. The code for this project is broken up into two jupyter notebooks: [Data collection and Cleaning](https://github.com/tpgkevin/memes/blob/main/Memes_Data_Collection_and_Cleaning.ipynb) and [Data Analysis and visuilization](https://github.com/tpgkevin/memes/blob/main/Memes_Data_Analysis.ipynb)
## Web-scraping for Memes Names
The first step in this project involved using the beautifulsoup library to webscrape knowyourmemes.com to collect the names of all the memes and compile them in a single database. The code can be found [here](https://github.com/tpgkevin/memes/blob/main/Memes_Data_Collection_and_Cleaning.ipynb) in the "Scraping for Meme Names" section. Most of this portion revolves around automating the scraping of the website's html code to parse out all meme names. This step required finding a way to deal with an infitenly scrolling page as well as a deeply nested html code.
## Meme Popularity
The next step was to find how popular every meme was
