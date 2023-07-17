# Text_similarity_graph
A tool that constructs a graph given text in a natural language as input, such that a node represents a sentence, and an edge exists from one sentence (node) to another if text similarity between the two is above a user-defined threshold.

the algorithm starts by spliting sentences into words in a list for each sentence, then converge each list into a set to remove duplicates then calculates similarity by calculating the intersection between words over the union of all the unique words in the two sentences given.

the second function draws the graph by using networkx library.
when the similarity exceeds the user entered threshold the function draws an edge between these two nodes. 
