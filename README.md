# Binary-Search-Tree-Keyword-Search

Background:
- Information retrieval systems allow users to enter keywords and retrieve articles 
  that have those keywords associated with them. For example, once a student named 
  Yi Li wrote a paper called, “Object Class Recognition using Images of Abstract 
  Regions," and included the following keywords: `object recognition', `abstract 
  regions', `mixture models', and `EM algorithm'. If someone does a search for all 
  articles about the EM algorithm, this paper (and many others) will be retrieved.
  
  
- A binary search tree that stores and retrieves articles. The tree is sorted by 
  keywords, and each node will contain an unordered linked list of Record objects 
  which contain information about each article that corresponds to that keyword. 
