# Document Search Covid-19

## Libraries  
Packages used (Python):  
numpy   
pandas   
json   
glob   
random   
nltk  
gensim  
sklearn  
matplotlib  
pyLDAvis  

## Project Motivation
With the current Covid-19 pandemic, the COVID-19 Open Research Dataset Challenge (CORD-19) was announced on Kaggle. The dataset contains a corpus of 200,000 scholarly articles about COVID-19, SARS-CoV-2, and other related coronaviruses. Which they have a problem sifting through.
Therefore, I implemented different methods to sift through the articles.  
Keyword Search, Cosine Similarity and Topic Modeling 

## File Descriptions
1. sifting-through-covid-19-articles.ipynb: This contains a class and functions to extract load and transform data, Keyword Search,      create a Cosine Similarity Matrix, and perform Topic Modeling.
2. Data Overview: This contains an overview of the data
## Results Summary 
Implemented  Keyword Search and Cosine Similarity functions and Topic Modeling to sift through the data COVID-19 Open Research Dataset Challenge (CORD-19)  
The discussion of the code can be found in a blog post [here](https://medium.com/@rhys.jervis94/sifting-through-covid-19-articles-66766ed02eab).

## Data
This [dataset](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) was created by the Allen Institute for AI in partnership with the Chan Zuckerberg Initiative, Georgetown University’s Center for Security and Emerging Technology, Microsoft Research, IBM, and the National Library of Medicine - National Institutes of Health, in coordination with The White House Office of Science and Technology Policy. It is updated regularly.

It contains a corpus of, "over 200,000 scholarly articles, including over 94,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses". Although the documents have the structure define by json_schema.txt. However, as each article has varying authors, sections, missing data, etc, custom functions had to be created. 

Given the large size of the corpus, a subset will be examined.

The number of topics chosen for the Latent Dirichlet Allocation (LDA) is a hyperparameter and is usually chosen through trial and error. KMeans is used to determine  a starting point 

## Acknowledgements 
Created as part of the Udacity Data Scientist Nanodegree Program.


