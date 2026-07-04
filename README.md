# Natural-Language-Processing
## Overview

Searching for relevant research papers from a large collection can be difficult because keyword-based search does not always return the most meaningful results. This project solves that problem by using Natural Language Processing (NLP) techniques to perform semantic search. Instead of matching only keywords, it understands the meaning of the query and retrieves the most relevant research papers.

After retrieving the papers, the project also generates a summary, extracts important keywords, identifies named entities, and provides simple visualizations to better understand the data. This project helped me understand how different NLP techniques can be combined to build a complete research paper search system.
## Features
-> Semantic search using Sentence Transformers

-> Fast paper retrieval using FAISS

-> Cosine similarity for matching research papers

-> Search time calculation

-> Automatic text summarization

-> Keyword extraction using KeyBERT

-> Named Entity Recognition (NER)

-> PCA visualization of text embeddings

-> Word frequency visualization
## Technologies Used
Technology           	Purpose
Python	              Programming Language
Pandas	Data processing
Sentence Transformers	Text embeddings
FAISS	Fast similarity search
Transformers	Summarization and NER
KeyBERT	Keyword extraction
Scikit-learn	Cosine similarity and PCA
Matplotlib	Data visualization


| **Technology**            | **Purpose**                                                            |
| ------------------------- | ---------------------------------------------------------------------- |
| Python                    | Programming language used to build the project.                        |
| Pandas                    | Data loading, cleaning, and preprocessing.                             |
| NumPy                     | Numerical computations and array operations.                           |
| Sentence Transformers     | Generated sentence embeddings for semantic search.                     |
| FAISS                     | Performed fast similarity search on embeddings.                        |
| Scikit-learn              | Used PCA for embedding visualization and cosine similarity.            |
| Hugging Face Transformers | Generated text summaries and performed Named Entity Recognition (NER). |
| KeyBERT                   | Extracted important keywords from research paper abstracts.            |
| Matplotlib                | Created graphs and visualizations.                                     |
| spaCy                     | Processed text and supported Named Entity Recognition.                 |
| Regular Expressions (re)  | Cleaned and processed text data.                                       |
| Collections (Counter)     | Calculated word frequency for visualization.                           |

## Dataset

This project uses the ML ArXiv Research Papers Dataset. The dataset contains research paper titles and abstracts. For this project, the title and abstract were combined into a single text column so that better semantic embeddings could be generated.

### The main columns used in the project are:

| **Item**      | **Description**                                                                       |
| ------------- | ------------------------------------------------------------------------------------- |
| Dataset Name  | ML ArXiv Research Papers Dataset                                                      |
| Source        | Hugging Face Datasets                                                                 |
| Data Used     | Research paper titles and abstracts                                                   |
| Main Columns  | Title, Abstract, Paper Text                                                           |
| Purpose       | To perform semantic search and NLP-based analysis on research papers                  |
| Preprocessing | Combined text, removed unnecessary values, and prepared data for embedding generation |

## Project Workflow
1.Load the research paper dataset.

2.Prepare and clean the text.

3.Generate sentence embeddings.

4.Measure semantic similarity.

5.Create a FAISS index.

6.Search the most relevant papers.

7.Measure search time.

8.Generate a summary.

9.Extract keywords.

10.Perform Named Entity Recognition (NER).

11.Visualize embeddings and word frequency.
## Libraries Used
pandas,
numpy,
datasets,
sentence-transformers,
faiss-cpu,
transformers,
keybert,
scikit-learn,
matplotlib,
spacy.
## Output
After entering a search query, the system displays:

Research paper title,
Similarity score,
Abstract,
Generated summary,
Important keywords,
Named entities,
Search time.
## Visualizations

The project also includes simple visualizations to better understand the generated text embeddings and dataset.

PCA visualization of text embeddings
Word frequency bar chart

These visualizations help explain how the embedding model represents different pieces of text and show the most frequently occurring words in the dataset
## Result
| **Feature**                    | **Result**                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Dataset Loading                | Research paper dataset was loaded successfully.                                                                                                   |
| Text Preprocessing             | Text was cleaned and prepared for further analysis.                                                                                               |
| Sentence Embeddings            | Meaningful embeddings were generated using Sentence Transformers.                                                                                 |
| Semantic Search                | Relevant research papers were retrieved based on the user's query.                                                                                |
| FAISS Indexing                 | Fast and efficient similarity search was achieved using FAISS.                                                                                    |
| Similarity Matching            | Cosine similarity was used to identify the most relevant papers.                                                                                  |
| Search Time Analysis           | Search execution time was successfully measured.                                                                                                  |
| Text Summarization             | Short summaries of retrieved research papers were generated.                                                                                      |
| Keyword Extraction             | Important keywords were extracted using KeyBERT.                                                                                                  |
| Named Entity Recognition (NER) | Entities such as organizations, people, and locations were identified from the text.                                                              |
| Data Visualization             | PCA visualization and word frequency charts were generated to understand the text data better.                                                    |
| Overall Outcome                | The system successfully combined semantic search and multiple NLP techniques to provide an efficient research paper search and analysis solution. |

## Future Improvements

### In the future, this project can be improved by:

->Searching from larger research paper collections.

->Building a web application for easier use.

->Supporting PDF document search.

->Using more advanced summarization models.

->Adding filters such as publication year or research domain.
## Conclusion

This project demonstrates how NLP can be used to make research paper searching more meaningful and efficient. Instead of relying only on keyword matching, it uses semantic search to understand the user's query and retrieve relevant papers. Features like summarization, keyword extraction, Named Entity Recognition, and visualizations make the retrieved information easier to understand. Overall, this project provided practical experience with sentence embeddings, FAISS, semantic search, and other important NLP concepts while building a complete research paper search system.
