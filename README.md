# Constitution PDF - RAG Question Answering System

A RAG (Retrieval Augmented Generation) based question answering system that lets you ask questions about the Indian Constitution PDF using AI.

## Tech Stack
- LangChain - PDF loading and text splitting
- SentenceTransformers - Text embeddings (all-MiniLM-L6-v2)
- ChromaDB - Vector database for storing embeddings
- Google Gemini AI - Answer generation
- Python - Core language

## How It Works
1. PDF load hoti hai LangChain se
2. Text 500 character chunks me split hota hai
3. Har chunk ka embedding generate hota hai
4. Embeddings ChromaDB me store hote hain
5. Query aane par relevant chunks retrieve hote hain
6. Gemini AI context se answer generate karta hai

## Setup

### Install Dependencies
pip install langchain chromadb sentence-transformers google-genai

### API Key
Google AI Studio se API key lo - aistudio.google.com

### Run
Google Colab me open karo aur cells ek ek karke run karo

## Project Structure
constitution-rag/
├── rag_constitution.ipynb
├── README.md
└── requirements.txt

## Author
saksham966 - Learning AI/ML development
