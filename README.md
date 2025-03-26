# LLM-Based-Cell-Type-Annotation-of-scRNA-seq-Data
This project demonstrates how to annotate clusters from single-cell RNA sequencing (scRNA-seq) data using a pretrained Large Language Model (LLM) without manual marker lookup.

## 🔍 What it does

- Loads scRNA-seq data (e.g. PBMC 3k)
- Clusters cells using Leiden and UMAP
- Extracts top marker genes per cluster
- Uses an LLM (`google/flan-t5-large`) to annotate cell types
- Visualizes UMAP with cell-type labels
