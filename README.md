# AI-Powered Legal Document Assistant
# 🧠 AI-Powered Legal Document Review Assistant

An intelligent Retrieval-Augmented Generation (RAG) system designed to analyze and reason over complex EU AI regulations using LLM-powered semantic retrieval and contextual grounding.

This project demonstrates how Large Language Models can be enhanced with vector search and tool-based reasoning to create an AI assistant capable of navigating and interpreting large legal documents efficiently.

---

## 🚀 Project Overview

Legal regulations are often lengthy, technical, and difficult to interpret.  
This system allows users to:

- 🔎 Ask natural language questions about EU AI regulations  
- 📚 Retrieve relevant legal clauses using semantic search  
- 🧠 Generate context-aware answers using GPT-4o  
- ⚖️ Understand complex legal terminology with AI-assisted reasoning  
- 📊 Receive grounded responses based strictly on document content  

The assistant leverages a Retrieval-Augmented Generation (RAG) pipeline to reduce hallucination and ensure factual grounding.

---

## 🏗️ System Architecture

### 🔧 Tech Stack

- **LLM:** OpenAI GPT-4o  
- **Embeddings:** OpenAI Embedding Models  
- **Vector Database:** ChromaDB  
- **Agent Framework:** LangChain  
- **Frontend Interface:** Streamlit  

---

## 🔁 System Workflow

1. 📄 Legal documents are chunked and processed.
2. 🧮 Text chunks are converted into embeddings.
3. 🗄️ Embeddings are stored in ChromaDB.
4. 🧠 User submits a query.
5. 🔎 The system performs semantic similarity search.
6. 📚 Top-K relevant legal sections are retrieved.
7. 🤖 Retrieved context is passed into GPT-4o.
8. 📝 The model generates a grounded, context-aware legal response.
9. 💻 Response is displayed via the Streamlit interface.

---

## 🔍 System Design Diagram

User Query
│
▼
Semantic Search (ChromaDB)
│
▼
Top-K Relevant Legal Chunks
│
▼
GPT-4o (LLM Reasoning)
│
▼
Grounded Legal Response
│
▼
Streamlit Interface


---

## 🎯 Key Features

- Retrieval-Augmented Generation (RAG) implementation  
- Semantic vector search over large legal documents  
- Context-aware legal Q&A  
- Reduced hallucination through grounded retrieval  
- Modular and extensible architecture  
- Interactive UI using Streamlit  

---

## 💻 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd <repo-name>

### 2️⃣ Set OpenAI API Key
```bash
export OPENAI_API_KEY=your_key_here


(For Windows PowerShell)

setx OPENAI_API_KEY "your_key_here"

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application

Navigate to the app folder:

cd app
streamlit run app.py


The application will launch locally in your browser.
