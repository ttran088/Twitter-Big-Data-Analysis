Overview
-------

Crawler

This application uses the Twitter Streaming API to collect geolocated tweets and stores them in text files of 10MB each.

Instructions on how to deploy the system
-------

In order to run the program, you must have: 

* Python 2.7
* Tweepy Twitter API library installed.
* lxml 

Download the repository from https://github.com/ttran088/Twitter-Big-Data-Analysis.git

If on Unix/Linux, run the crawler.sh shellscript, and pass the number of tweets you want to search (if the number is 0, the crawler will go on untill it reaches 5 GB in data) and output directory name, which will execute the Python program. 

By default, the files are placed in /data and number of tweets are not limited. 

Examples:

1. ./runCrawler.sh [num-tweets] [output-dir] 
2. ./runCrawler.sh [num-tweets]
3. ./runCrawler.sh 