# recommendation-engine-with-topic-modelling
textsummarization
Summarization is a useful tool for varied textual applications that aims to highlight important information within a large corpus. With the outburst of information on the web, Python provides some handy tools to help summarize a text. This article provides an overview of the two major categories of approaches followed - extractive and abstractive. In this article, we shall look at a working example of extractive summarization.
 

Algorithm : 
Below is the algorithm implemented in the gensim library, called "TextRank", which is based on PageRank algorithm for ranking search results.

Pre-process the given text. This includes stop words removal, punctuation removal, and stemming.
Make a graph with sentences that are the vertices.
The graph has edges denoting the similarity between the two sentences at the vertices.
Run PageRank algorithm on this weighted graph.
Pick the highest-scoring vertices and append them to the summary.
Based on the ratio or the word count, the number of vertices to be picked is decided.
