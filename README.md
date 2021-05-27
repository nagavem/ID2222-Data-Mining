# ID2222-Data-Mining
Course Work from the course data mining from my Master's Program at KTH Royal Institute of Technology

Includes the 5 assignments present as a part of this course.

# Assignment 1: Finding Similar Items - Textually Similar Documents

Implement the stages of finding textually similar documents based on Jaccard similarity using the shingling, minhashing, and locality-sensitive hashing (LSH) techniques and corresponding algorithms.

You do not have to develop the exact same classes and data types as described below. Feel free to use data structures that suit you best.

* A class Shingling that constructs k–shingles of a given length k (e.g., 10) from a given document, computes a hash value for each unique shingle, and represents the document in the form of an ordered set of its hashed k-shingles.
* A class CompareSets that computes the Jaccard similarity of two sets of integers – two sets of hashed shingles.
* A class MinHashing that builds a minHash signature (in the form of a vector or a set) of a given length n from a given set of integers (a set of hashed shingles).
* A class CompareSignatures that estimates similarity of two integer vectors – minhash signatures – as a fraction of components, in which they agree.
* To test and evaluate scalability (the execution time versus the size of input dataset) of your implementation, write a program that uses your classes to find similar documents in a corpus of 5-10 documents. Choose a similarity threshold s (e.g., 0,8) that states that two documents are similar if the Jaccard similarity of their shingle sets is at least s. 

# Assignment 2: Discovery of Frequent Itemsets and Association Rules

The problem of discovering association rules between itemsets in a sales transaction database (a set of baskets) includes the following two sub-problems

1. Finding frequent itemsets with support at least s;
2. Generating association rules with confidence at least c from the itemsets found in the first step.

Implement the A-Priori algorithm for finding frequent itemsets with support at least s in a dataset of sales transactions. Remind that support of an itemset is the number of transactions containing the itemset. To test and evaluate your implementation, write a program that uses your A-Priori algorithm implementation to discover frequent itemsets with support at least s in a given dataset of sales transactions.

The implementation can be done using any big data processing framework, such as Apache Spark, Apache Flink, or no framework, e.g., in Java, Python, etc.  

