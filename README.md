# Benno RAG Assistant

A simple Retrieval-Augmented Generation (RAG) chatbot built with LlamaIndex, Groq (LLaMA 3), and HuggingFace embeddings.

## 🚀 Features

* Custom knowledge base (Benno & Timmy profiles)
* Semantic search using embeddings
* Context-aware responses using RAG
* Chat interface built with Gradio
* Memory support via LlamaIndex ChatEngine

## 🧠 Tech Stack

* Python
* LlamaIndex
* Groq API (LLaMA 3)
* HuggingFace Embeddings
* Gradio

## 📂 Project Structure

```
RAG.ipynb        # Main notebook with full pipeline
data/            # Custom text data (generated in notebook)
```

## ⚙️ How it works

1. Load custom data
2. Split text into chunks
3. Generate embeddings
4. Store in vector index
5. Retrieve relevant context
6. Generate answer using LLM

## ▶️ Run the project

1. Open the notebook in Google Colab
2. Add your Groq API key
3. Run all cells
4. Launch the Gradio interface

## 🧪 Example Questions

* "How old is Benno?"
* "What are Bennos goals?"
* "Who is Timmy?"

## ⚠️ Notes

* This project runs in a notebook environment (Colab)
* Memory behavior may differ depending on runtime session
* Stateless and stateful chat versions are included

## 📌 Future Improvements

* Persistent user memory (database)
* Multi-user support
* File upload (PDF, etc.)
* Deployment as web app

---

Built as a learning project for RAG systems and LLM applications.
