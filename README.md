# 🤖 End-to-End RAG Application

An interactive Retrieval-Augmented Generation (RAG) system built to query custom domain knowledge and external documents using Large Language Models (LLMs) and Vector Embeddings.

---

## 📌 Features

* 📄 **Document Indexing:** Loads, chunks, and processes custom data (PDFs, TXT, JSONL).
* 🔍 **Vector Search:** Converts text into embeddings and retrieves the most relevant contexts.
* 💬 **Context-Aware Responses:** Generates accurate answers based strictly on retrieved domain knowledge.
* 🎨 **Interactive UI:** Simple and clean user interface powered by Streamlit.

---

## 📁 Repository Structure

```text
end-to-end-rag-app/
├── app.py              # Main frontend application (Streamlit UI)
├── requirements.txt    # Project dependencies and libraries
├── README.md           # Project documentation
├── books.jsonl         # Knowledge base sample dataset
└── src/                # Backend logic and helper scripts
    ├── __init__.py
    ├── loader.py       # Data loading and preprocessing logic
    ├── embeddings.py   # Embedding generation and vector store setup
    └── rag_chain.py    # LLM integration and retrieval pipeline
