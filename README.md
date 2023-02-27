# Delegates Information Extraction 
## Abstract 
Merger and Acquisition (M & A) activity is exponentially increasing with time and has increased from $1400 billion to $2600 billion in the USA in the past 15 years. Information of M&A deals between two organizations is readily available on the internet. However, to get further insights into the data, one must go further into the press release or blogs to get information about the delegations involved. In this work, we consider extracting the delegate’s information like name and job position of the people involved in the process using various NLP techniques.

## Introduction
The terms "merger" and "acquisition" are frequently and
synonymously used in the business world. However, both
actually mean different things. While an acquisition occurs
when one corporate organization totally or partially takes
over the target company, a merger refers to the joining of
two businesses or organizations into one. Even while
Merger and Acquisition (M&A) requires a lot of work and
significant input from all departments of the organization,
executives like the CEO, CFO, and vice president plays a
crucial role in formulating strategies, making final deal
decisions, and even anticipating even post-deal happenings.
Generally, to gain media and public attention, companies
put press releases with acquisition announcements with all
the essential details. Most of the deals information are also
kept in publicly accessible U.S. Securities and Exchange
Commission (SEC)[1] database.  
The USA signed most of the M&A deals in 2021, at f
$2549 billion followed by China and UK with the value of
$528 billion and $347 billion respectively[2]. Information
related to these deals are readily available in the internet in
the form of press releases from the companies or blog posts
on famous websites (BusinessWire, PR Newswire etc.) ,but
getting names and job title of all delegates (CEO, CFO, VP
etc.) from both sides of the deal, we have to read one or
multiple articles manually. Collecting and storing all the
information manually is a very tedious and timeconsuming
process.  
So in this work, we have automated this task of
identifying the executives mentioned in company press
releases information using web scraping and NLP
techniques like relationship extraction and Named Entity
Recognition.  

## Files:  
Many files will be created after executing the code.   
original_data.csv - code file with labels   
mergers.xlsx - data we need to do labeling on. 

Code.py: main code file  
metrics.py: code file to check NER results  

- metadata.csv: are files that contains company name and the file name in which there fetched textual data is stored  
- ner_fetched.csv: update of metadata.csv -> after pre processing : contains columns with person names, organziation names, and job titles  
- job_lists.txt: all job titles fethced from the website  
- jobLists_subset.csv: all job titles of buisness domain only. this file is subset of above file(job_lists.txt)    

fetched  : this folder conatins all json(fethced textual data for each deal) files (step3())   


