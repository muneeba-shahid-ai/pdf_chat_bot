
# 📘 PDF Chat Index

A web-based AI application that allows users to upload PDF documents and ask natural language questions about their content — powered by **OpenAI**, **Pinecone**, and **Streamlit**.

---

## 🚀 Features

- 📄 **Upload PDFs** — Easily upload any PDF file.  
- 💬 **Ask Questions** — Interact with your document using natural language queries.  
- 🧠 **Semantic Search** — Uses **OpenAI embeddings** to understand the meaning behind your questions.  
- ⚡ **Vector Indexing** — Efficient document retrieval with **Pinecone** vector database.  
- 🖥️ **Streamlit Interface** — Simple, intuitive, and interactive web interface.

---

## 🧩 Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **AI / NLP:** OpenAI Embeddings, GPT Models  
- **Vector Database:** Pinecone  

---

## 🏗️ How It Works

1. **Upload** a PDF document.  
2. The system splits the text into chunks and **embeds** them using OpenAI embeddings.  
3. These embeddings are stored in **Pinecone** for fast similarity search.  
4. When you ask a question, the app retrieves the most relevant chunks from Pinecone.  
5. Finally, **GPT** generates a coherent and context-aware answer using the retrieved content.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/muneeba-shahid-ai/pdf_chat_index.git
cd pdf_chat_index
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set Environment Variables

Create a `.env` file and add:

```bash
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
PINECONE_ENV=your_pinecone_environment
```

### 4️⃣ Run the App

```bash
streamlit run app.py
```

---

## 🧪 Example Use Case

Upload a research paper, report, or eBook, and ask:

> “What are the key findings in section 3?”
> “Summarize the main conclusion.”
> “Who are the authors and what problem are they solving?”

---

## 🧰 Future Improvements

* Support for multiple document uploads
* Enhanced summarization and answer confidence scoring
* Integration with local storage or other vector DBs (FAISS, Chroma)

---

## 🤝 Contributing

Pull requests are welcome!
If you find a bug or want to suggest a feature, feel free to open an issue.

---

## 📜 License

This project is licensed under the **MIT License**.

---

