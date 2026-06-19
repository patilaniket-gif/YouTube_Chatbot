# YouTube_Chatbot

## 📖 Description
This project is an AI-powered chatbot that allows users to ask questions about a YouTube video's content. The system extracts the video transcript, processes it into searchable chunks, and uses a Large Language Model (LLM) with Retrieval-Augmented Generation (RAG) to provide accurate, context-aware answers based on the video's content.


## 🎯 Objective
-Build an AI chatbot for YouTube videos.
-Answer user questions from video transcripts.
-Improve answer accuracy using RAG.
-Provide a simple and interactive user interface.

## 🛠️ Technologies Used
-Python
-LangChain
-Google Gemini API / OpenAI API
-FAISS (Vector Database)
-Hugging Face Embeddings
-YouTube Transcript API
-Streamlit
-dotenv

## ⚙️ Features
-Extracts YouTube video transcripts automatically.
-Converts transcript into searchable embeddings.
-Uses RAG for accurate responses.
-Answers questions in natural language.
-Fast semantic search using FAISS.
-Simple Streamlit web interface.

## 📂 Project Structure
YouTube_Chatbot/
│── app.py
│── requirements.txt
│── .env
│── utils.py
│── rag_pipeline.py
│── transcript_loader.py
│── embeddings.py
│── vector_store/
└── README.md

## ▶️ Usage
-Launch the application.
-Enter a YouTube video URL.
-The transcript is extracted and indexed.
-Ask questions related to the video.
-The chatbot returns context-based answers.

## 📊 Results
-Successfully retrieves YouTube transcripts.
-Generates accurate answers using RAG and LLM.
-Provides fast, interactive question-answering with a user-friendly interface.

## 📌 Conclusion
The YouTube Chatbot demonstrates how LLMs and RAG can transform video content into an interactive knowledge source, enabling users to quickly find information without watching the entire video.

## 🔮 Future Work
-Support multiple YouTube videos.
-Add multilingual transcript translation.
-Enable voice input and speech output.
-Store chat history.
-Improve retrieval accuracy with advanced reranking.
-Deploy the application on cloud platforms.
