# Pandora: AI Counselor Bot 🤖💬

## 📚 Abstract
Pandora is an AI-driven virtual counselor designed to provide preliminary emotional support to students dealing with stress, loneliness, anxiety, and depression.
The system uses Retrieval-Augmented Generation (RAG) to offer empathetic, safe, and human-like conversations.

## 🚀 Technologies Used
- Python 3.10
- HuggingFace Transformers
- SentenceTransformers (MiniLM-L6-v2)
- FAISS (Facebook AI Similarity Search)

## 🏛 System Architecture
User Input ➔ RAG Search ➔ Warm Response

## 📦 Folder Structure
Group7_PandoraCounselor/
├── report.pdf
├── slides.pptx
├── README.md
├── src/
│   ├── counselor_demo_app_rag_only.py
│   ├── counselor_faiss.index
│   ├── counselor_responses.json
│   └── intents_cleaned.json

## 🛠 How to Run
```bash
pip install faiss-cpu sentence-transformers
python src/counselor_demo_app_rag_only.py
```

💬 Sample Chat
User: I feel sad.
Pandora: It's okay to feel sad sometimes. You're not alone.

👩‍💻 Developed by: Michelle and Radhika
