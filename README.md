#  RAG Chatbot using Ollama

A Retrieval-Augmented Generation (RAG) chatbot that answers questions about C++ using a custom C++ knowledge document.

The application uses Streamlit for the user interface, LangChain for the RAG pipeline, Hugging Face for text embeddings, FAISS for vector similarity search, and Ollama with the Gemma 2B model for generating answers.

##  Features

- Interactive Streamlit chatbot interface
- Uses a custom C++ knowledge document
- Splits documents into smaller chunks
- Generates embeddings using Hugging Face
- Stores embeddings in FAISS
- Retrieves relevant C++ information using similarity search
- Uses Ollama to run a local Gemma 2B language model
- Generates answers based only on the retrieved context
- Uses Streamlit caching for efficient vector-store loading

## Technologies Used

- Python
- Streamlit
- LangChain
- Hugging Face
- Sentence Transformers
- FAISS
- Ollama
- Gemma 2B

## Project Structure

```text
AI_WORKSHOP/
│
├── app.py
├── C++_Introduction.txt
├── requirements.txt
├── README.md
├── .gitignore
└── myenv/
