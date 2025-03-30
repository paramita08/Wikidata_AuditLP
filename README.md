# Social Biases in Knowledge Representations of Wikidata separates Global North from Global South

Accepted at ACM WebSci’25
Paramita Das, Sai Keerthana Karnam, Aditya Soni, Animesh Mukherjee. 

## Abstract
Knowledge Graphs have become increasingly popular due to their wide usage in various downstream applications, including information retrieval, chatbot development, language model construction, and many others. Link prediction (LP) is a crucial downstream task for knowledge graphs, as it helps to address the problem of the incompleteness of the knowledge graphs. However, previous research has shown that knowledge graphs, often created in a (semi) automatic manner, are not free from social biases. These biases can have harmful effects on
downstream applications, especially by leading to unfair behavior toward minority groups. To understand this issue in detail, we develop a framework – AuditLP – deploying fairness metrics to identify biased outcomes in LP, specifically how occupations are classified as either male or female-dominated based on gender as a sensitive attribute. We have experimented with the sensitive attribute age and observed that occupations are categorized as young-biased, old-biased, and age-neutral. We conduct our experiments on a large number of knowledge triples that belong to 21 different geographies extracted from the open-sourced knowledge graph, Wikidata. Our study shows that the variance in the biased outcomes across geographies neatly mirrors the
socio-economic and cultural division of the world, resulting in a clear partition of the Global North from the Global South.

## 📚 Dataset Preparation and Embedding Generation
The steps for preparing the dataset and generating embeddings are detailed at the following URL:

➡️ [Dataset Preparation and Embedding Generation](https://github.com/paramita08/Wikidata_Bias_WebSci_2023)

---

## 🧩 Code
The main code for link prediction is contained in the Jupyter Notebook:

➡️  [`LP_occupation_analysis.ipynb`](./LP_occupation_analysis.ipynb)

This notebook performs the following tasks:
- Loads the preprocessed dataset, embeddings and models.
- Finds Gender Biased and Neutral Occupations.

---

## 📦 Preprocessed Dataset and Embeddings
The preprocessed dataset, along with the generated embeddings, can be accessed at:

➡️ [Preprocessed Dataset and Embeddings](url)
