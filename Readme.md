# Scientific Abstract Information Extraction
NLP pipeline for extracting structured insights from food-science article abstracts using topic modelling, document embeddings, and rule-based phrase extraction.
## What this project is about
This project explores how natural language processing can be used to turn research article abstracts into more structured and searchable information.

The dataset used here contains food-journal article records, including:
- authors,
- journal name,
- article title,
- and abstract text.

The aim is not only to group similar articles together, but also to extract useful information such as:
- what the study is trying to do,
- how it was carried out,
- what kind of findings are being reported,
- and what broad themes are present across the collection.

## Why this matters
Scientific abstracts contain a lot of useful information, but it is often buried in free text.

This repository builds a pipeline that helps transform those abstracts into something more structured through:
- text cleaning and preprocessing,
- sentiment-style screening,
- document embeddings,
- topic modelling,
- and rule-based information extraction.

## What the repository does
This project:
1. loads and cleans article metadata and abstracts,
2. removes records with missing abstracts,
3. tokenises and normalises the abstract text,
4. builds document representations,
5. identifies broad document themes,
6. extracts summary-like phrase structures from sentences,
7. groups similar abstracts together.

## Main files
- `NLP_portsmouth_Final.ipynb`  
  Main end-to-end notebook for preprocessing, modelling, topic discovery, phrase extraction, and clustering.

- `NLP_portsmouth-Copy1.ipynb`  
  Earlier or working-copy notebook.

- `Overall_pipeline.png`  
  High-level visual overview of the workflow.

- `Dashboard 1.png`  
  Example output/dashboard image.

## What a non-technical reader should take away
This is a project about making research abstracts easier to interpret at scale.

Instead of reading thousands of abstracts one by one, the pipeline helps identify:
- common themes,
- likely study aims and findings,
- and groups of related papers.

## Main methods used
- text cleaning and tokenisation
- document embeddings
- topic modelling
- dependency/POS-based phrase extraction
- clustering and low-dimensional visualisation
