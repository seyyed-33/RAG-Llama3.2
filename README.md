# RAG with Llama 3.2

This project implements a simple **RAG (Retrieval-Augmented Generation)** system using **Llama 3.2** and **FAISS**. It retrieves relevant documents from a vector database and generates answers based on them.

## Features
- Document retrieval using FAISS
- Local LLM inference with Ollama (Llama 3.2)
- Question answering based on retrieved context

## Technologies Used
- Python
- LangChain
- FAISS
- Ollama
- Llama 3.2

## How to Run
1. Clone the repository
2. Make sure Ollama is running and the `llama3.2` model is available
3. Open the notebook:
   ```bash
   jupyter notebook rag_llama.ipynb