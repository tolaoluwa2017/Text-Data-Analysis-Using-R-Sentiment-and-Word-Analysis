Project Title:
Text Mining and Sentiment Analysis of Book Reviews Using R

Project Overview:
This project applies Natural Language Processing (NLP) techniques to analyze book reviews. The goal is to explore sentiment trends, extract important keywords, and classify books based on textual sentiment and rating data. Various text processing methods, word frequency distributions, and Latent Dirichlet Allocation (LDA) topic modeling are applied to uncover hidden themes within the reviews.

The insights gained from this analysis can be beneficial for publishers, authors, and readers to understand book reception and user sentiment.

Methodology:
1. Data Preprocessing and Cleaning
Loaded book review data, filtering reviews between 200-400 characters for quality.
Converted text to lowercase, removed punctuation, numbers, stopwords, and applied stemming.
Created a Term Document Matrix (TDM) for further analysis.
2. Word Frequency Analysis
Identified the top 10 most frequent words.
Filtered terms appearing in more than 10% of reviews and removed rare words.
Generated word frequency histograms and word clouds.
3. Sentiment Analysis
Used the Bing Lexicon for sentiment scoring.
Analyzed sentiment distribution using histograms.
Compared average sentiment scores across different books.
4. Topic Modeling with LDA
Performed Latent Dirichlet Allocation (LDA) to detect themes in book reviews.
Visualized top words in each topic using bar plots.
Tuned the optimal number of topics (k) using perplexity scores.
5. PCA & Non-Negative Matrix Factorization (NMF)
Applied Principal Component Analysis (PCA) for dimensionality reduction.
Used NMF to detect latent topics in book reviews.
Generated document-topic heatmaps to visualize associations.
Results and Insights:
1. Word Frequency Analysis
The most common words include “book,” “read,” “story,” “recommend,” and “love”.
Filtering rare words helped improve the quality of topic modeling.
2. Sentiment Analysis Findings
The histogram of Bing sentiment scores shows a bimodal distribution:
Many reviews are highly positive or highly negative, with fewer neutral reviews.
Boxplot Analysis:
Some genres have a higher spread in sentiment, indicating varied reactions.
Higher-rated books tend to have higher sentiment scores, confirming alignment between ratings and textual sentiment.
3. Topic Modeling and Key Findings
LDA identified five major topics, with top words in each providing insight into dominant themes.
The best value of k for topic modeling was determined through perplexity analysis.
PCA visualization helped show clear clusters of book reviews based on sentiment.
Conclusion & Future Work
This project successfully extracted meaningful insights from book reviews through text mining, sentiment analysis, and topic modeling. The findings indicate that sentiment scores align with book ratings, and topic modeling reveals key themes in book discussions.

Future Enhancements:
Expanding sentiment analysis to use Deep Learning models (e.g., BERT, GPT-3).
Applying neural networks for improved topic modeling.
Integrating a recommendation system based on review sentiment and topic clusters.
