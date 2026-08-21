# Multi-Document Research Agent

A LlamaIndex-based AI agent that answers questions and compares information across multiple research papers.

For every PDF, the project creates:

* A **vector search tool** for answering specific questions.
* A **summary tool** for generating document-level summaries.
* A **tool retriever** that selects the most relevant tools for each query.

## Technologies

* Python
* LlamaIndex
* OpenAI
* Vector embeddings
* Retrieval-Augmented Generation (RAG)
* Function-calling agents
