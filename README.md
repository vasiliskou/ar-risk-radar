# 🧭 AI-Risk Radar: Monitoring Global AI Developments with LLMs & Clustering

AI-Risk Radar is a Colab-based pipeline and interactive dashboard that **tracks emerging AI-related risks, policy trends, and global developments** by scraping news, embedding content, clustering similar articles, labeling topics with LLMs, and summarizing insights — all visualized through a powerful Gradio interface.

---

## 🚀 Try It Instantly

Launch in your browser with one click:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nV0HOFwkDjabC0RQz4VvPIsHE3dXfhtU?usp=sharing)


---

## 🔍 What It Does

- 📰 **Scrapes AI news** from trusted global tech & policy feeds (e.g., UN, MIT Tech Review, Brookings)
- 🔎 **Embeds and clusters articles** by semantic similarity (via sentence-transformers + ChromaDB)
- 🧠 **Labels each cluster** using OpenAI's `gpt-4o-mini`
- 📝 **Summarizes clusters** to provide a digestible view of key themes
- 💬 **Interactive Gradio dashboard** to explore and download AI news trends by topic
- 📅 Optional: Generate a **weekly policy report** from recent global AI developments

> ✅ Fully functional in **Google Colab**, including on **CPU-only environments**

---

## 📷 Sample Output Screenshot

![App Screenshot](https://drive.google.com/uc?export=view&id=1et_ElpJn1Em2ABsBcoCVRJJEqr4Zp5ZB)

--- 


## 📦 Installation

All required packages are installed within the notebook:

```bash
pip install openai newspaper3k feedparser \
             sentence-transformers chromadb umap-learn hdbscan \
             plotly dash langchain-community lxml-html-clean gradio
