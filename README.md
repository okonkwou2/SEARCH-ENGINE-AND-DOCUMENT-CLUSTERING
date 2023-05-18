# SEARCH-ENGINE-AND-DOCUMENT-CLUSTERING-USING-PYTHON

A search engine is a software system that is designed to carry out web searches. They search the web in a systematic manner for specific information based on a textual web search query. The search results are generally presented in a line of outputs which are often referred to as the search engine results pages (SERPs). The output information retrieved could be links to web pages, images, videos ,articles, infographics, research papers and other relevant search outputs. Web search engines get their information by crawling the web from url sites to another. First the restrictions on the type of information or amount of information is checked before the crawling task is commenced using the “robots.txt” to be on the safe side. The robots.txt basically contains directives for crawlers telling which pages to crawl and which ones not to. After checking for the robots.txt, the crawler then sends the crawled information back to be indexed in a limited period of time spent on the web sites. A query from a user could be a single word or a sentence with specific words. The index helps find information relating to the query as quickly as possible. 
 The search engine maintains the following processes in real time:
•	Web crawler
•	Indexing
•	Query processor
In this task I will be carrying out this steps in developing a search engine. The data will be obtained from the coventry university pureportal web pages. This vertical search engine specialises in retrieving only publications strictly by members of the School of Humanities (SH) at Coventry University: https://pureportal.coventry.ac.uk/en/organisations/school-of-humanities.

DOCUMENT_CLUSTERING
In this task I performed document clustering using the KMeans clustering algorithm. My document was generated manually from the cnn news rss feed. It was generated from five different news sections which are US politics, health, sports, entertainment and business rspectively. A total of 133 different documents was collected from this five various news sections. 

TOPIC_MODELLING
 I decided to carryout one extra text clustering/classifaction analysis on the dataset to compare the result using the latent dirichlet allocation (LDA) which a topic modelling algorithm. I want to determine the hidden topics in this document. The core idea is to take a matrix of documents and terms and try to decompose it into two separate matrices which are the document-topic matrix and the topic term matrix by way of dimension reduction or noise reducing technique.
