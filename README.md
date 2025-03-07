# BanglaFinGPT
A fine-tuned GPT model to simplify financial queries in Bangla and English for the people of Bangladesh

# 🚀 Features
* 🌐 Dual-Language Support: Seamlessly answers queries in Bangla and English.
* 📚 Financial Expertise: Specializes in Tax, VAT, Customs, and general finance.
* 🔍 Context-Aware Responses: Combines retrieved documents and Q&A generation for precision.
* 🤖 AI-Powered Assistance: Built for individuals and businesses needing accurate financial insights.

# ✨ About BanglaFinGPT
BanglaFinGPT is a fine-tuned version of Lama 3.2  specialized for financial tasks in Bangladesh. It enables users to effortlessly understand complex financial regulations and make informed decisions.

# Methodology
![image](https://github.com/user-attachments/assets/a94da92b-d262-45df-bea1-c5741bb3068b)

# 1. Project Overview
* A chatbot designed to answer finance-related queries in Bengali and English.
* Combines fine-tuning and Retrieval-Augmented Generation (RAG) for accurate responses.
* Built using BanglaLLama-3.2-3b-bangla-alpaca-orca-instruct-v0.0.1 fine-tuned on 10,412 Bengali-English Q&A pairs from National Board of Revenue (NBR) PDFs.
* Supports domain-specific finance queries with enhanced retrieval mechanisms.

# 3. Features
* ✅ Fine-tuned LLM for Bengali finance topics.
* ✅ Retrieval-Augmented Generation (RAG) for improved accuracy.
* ✅ Vector database for efficient information retrieval.
* ✅ Bilingual support (Bengali & English).
* ✅ Interactive UI with Streamlit.

# 4. Tech Stack
* LLM: BanglaLLama-3.2-3b
* Fine-tuning: Hugging Face Transformers
* Data Processing: PDF chunking, Q&A generation
* Retrieval: FAISS (Facebook AI Similarity Search)
* Framework: LangChain
* UI: Streamlit
* Storage: Vector database(FAISS) for embeddings

# 5. Project Architecture
* 1️⃣ Data Collection: Extracted Q&A pairs from NBR PDFs.
* 2️⃣ Fine-Tuning: Trained BanglaLLama-3.2-3b with finance-related data.
* 3️⃣ Embedding Generation: Converted text into vectors using FAISS.
* 4️⃣ Retrieval Process: Queries retrieve relevant finance information from the vector database.
* 5️⃣ Response Generation: LLM generates responses based on retrieved data.
* 6️⃣ User Interface: Interactive chatbot built with Streamlit.

# Application Image
![image](https://github.com/user-attachments/assets/a5d36786-bd59-44af-a960-03b5e6729519)

