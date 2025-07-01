# 🎬 Movie Recommendation System using Knowledge Graphs + GNN

This project demonstrates how to build a **knowledge graph-based movie recommender** system using **Graph Neural Networks (GNNs)**. It is designed as a beginner-friendly mini project to help understand key steps in GNN-based recommendation.

---

## 🔍 Project Overview

- 📊 **Dataset**: MovieLens 100k  
- 🧠 **Model**: Graph Convolutional Network (GCN)  
- 🧩 **Graph**: Users, Movies, Genres as nodes  
- 🔗 **Edges**: `rated`, `belongs_to`  
- 🎯 **Goal**: Recommend top-N movies using GNN embeddings

---

## 💡 Pipeline

1. **Preprocess** MovieLens 100k dataset
2. **Build Knowledge Graph** using NetworkX
3. **Convert** to PyTorch Geometric format
4. **Train** a GCN to learn node embeddings
5. **Recommend** movies via cosine similarity
6. **Evaluate** using Precision@k

---

## 📦 How to Run

### ✅ Prerequisites
Install dependencies:
```bash
pip install -r requirements.txt
