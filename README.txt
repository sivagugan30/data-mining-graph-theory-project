# Data Mining Graph Theory Project

This repository contains the implementation of a graph-based node classification task as part of the **Data Mining** course.

## 📁 Dataset Overview
- **Nodes:** 2,480
- **Classes:** 7
- **Each node** has:
  - A feature vector (from `features.npy`)
  - A label/class (from `labels.npy`)
  - Connections defined in an adjacency matrix (`adj.npz`)
- **Data splits** provided in `splits.json`

## 📦 Files
- `features.npy` — Node features
- `labels.npy` — Class labels
- `adj.npz` — Sparse adjacency matrix
- `splits.json` — Train/test splits

## 🧠 Objective
Train a model (e.g., GCN, GAT) to predict the class of each node using:
- Node features
- Graph structure (edges)

Team members:
Mohini, Sanju, Prasad, Siddish, Siva