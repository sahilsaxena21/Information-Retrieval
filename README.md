# Information Retrieval (IR)

This program builds an IR system using a set of 1000+ files from an open source dataset.

In general, NLTK library is used for text processing along with the following other libraries:

1. Whoosh to index a set of documents
2. Whoosh to read queries (topics) from the set given
3. Whoosh to produce output for each query
4. Pytrec eval to compare Whoosh's output relative to human judgments
