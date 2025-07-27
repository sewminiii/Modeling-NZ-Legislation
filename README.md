# AI-Driven Network Analysis of New Zealand Legislation

This repository contains the code and output used in my Master's thesis titled:  
**"AI-Driven Network Analysis of New Zealand Legislation System"**  
with a case study focused on the **Family Violence Act 2018**.

The study explores how advanced AI techniques, specifically large language models (LLMs), can extract legal relationships from unstructured legislation and analyze their structure using network science.

---

## Contents

- `NER_and_RE.ipynb`  
  Performs Named Entity Recognition and Relationship Extraction using LLMs to identify references, amendments, and repeals between Acts.

- `Calculate_centrality_measures.ipynb`  
  Computes centrality scores (Degree, Betweenness, Closeness, Eigenvector, PageRank) to assess the structural importance of each Act.

- `Community_detection_and_Topic_modelling.ipynb`  
  Applies Louvain community detection to group Acts and uses BERTopic for topic modeling on each community.

- `Community_visualization.ipynb`  
  Generates visualizations to show thematic communities and their internal structure.

- `Network_Visualization_using_Neo4j.ipynb`  
  Visualizes the full legislative network in Neo4j using Cypher queries.

- `adjacency_matrix_v2.csv`  
  Adjacency matrix derived from extracted legal relationships, used for network analysis.
  
- `NER_and_RE_output.json`  
  Output json file got from NER and RE process.

## Requirements

This project uses the following key packages:

- Python 3.10+
- Claude LLM using Anthropic API calls (model: claude-3-haiku-20240307)
- `pandas`
- `networkx`
- `pdfpumbler`
- `matplotlib`
- `bertopic`
- `neo4j`
- `scikit-learn`
- `sentence-transformers`

## GitHub Repository Usage

This repository is intended as a supplementary material for the thesis. Each notebook corresponds to a stage in the methodology and can be run independently. API keys are required for LLM-based scripts.

---

