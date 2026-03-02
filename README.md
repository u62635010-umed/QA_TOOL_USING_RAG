# QA_TOOL_USING_RAG
# 📄 GenAI Project: Custom PDF Q&A Tool using LLM (RAG)

A Retrieval-Augmented Generation (RAG) based Question-Answering system that allows users to ask questions from custom PDF documents using Large Language Models (LLMs).

---

## 🚀 Project Overview

This project implements a **PDF-based Question Answering Tool** using:

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Semantic Chunking
- Vector Database Retrieval

The system extracts content from PDFs (including OCR support), generates embeddings, stores them in a vector database, and retrieves relevant chunks to answer user queries accurately.

---

## 🧠 Tech Stack

- **Python**
- **LangChain**
- **OpenAI GPT-3.5**
- **OpenAI Embeddings**
- **ChromaDB (Vector Database)**
- **PyPDFLoader & UnstructuredPDFLoader**
- **Semantic & Recursive Chunking**

---

## ⚙️ How It Works

1. **PDF Loading**
   - Supports text-based and scanned PDFs
   - Hybrid approach (Text + OCR)

2. **Chunking Strategy**
   - Recursive chunking
   - Semantic chunking
   - Preserves contextual meaning

3. **Embedding Generation**
   - OpenAI Embeddings used
   - Converts text chunks into vector representations

4. **Vector Storage**
   - ChromaDB stores embeddings
   - Enables fast similarity search

5. **Retrieval-Augmented Generation**
   - Retrieves top relevant chunks
   - GPT-3.5 generates final contextual answer

---

## 🔄 RAG Pipeline
