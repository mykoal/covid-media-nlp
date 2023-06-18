# covid-media-nlp
Dynamic topic modeling and other NLP analyses (keyness, n-grams, etc) on 14,000 NYT news articles

* cleaning_corpora.ipynb: stripping the noisy rtf files into jsons
* analyzing_corpora.ipynb: NLP analyses on the corpora (keyness, n-gram, etc)
* dynamic_topic_modeling.ipynb: DTM AI/ML modeling techniques

### Topic modeling on NYT articles

* Topic Modeling is an unsupervised machine learning technique that looks for a specified number of __TOPICS__ presumed to be the possible meaning space behind a set of documents (i.e., _in this context these are the N things people are likely to talk about_). In an iterative procedure patterns of term co-occurrence (topics) are found across documents. 

* The result is that for each document each of the N topics has a probability distribution (summing to 1) indicating the likelihood or contribution of each topic to the document. Topics are rankings of terms.

* The question at hand: "What are the N things NYT articles have talked about in the domain of vaccines"

#### Steps

1. Build a DTM from the `body` text field
2. Set up a LDA model with a specified number of topics to discover
3. Run the modeling
4. Examine the topics by looking at the top ranked terms in each topic and evaluating the plausibility of them as semantic groups.
5. Use document topic distributions in analysis.

#### Topic Analysis




#### Note for future work - could do some analyzes just on the titles
* Clustering
* Looking at patterns over years 
* etc.
