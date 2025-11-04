# SummarEase

**SummarEase** is an AI-powered PDF summarization and learning assistant built with **Streamlit** and **Generative AI**.  
It helps you extract, understand, and interact with lengthy documents effortlessly.  
> _Read less. Learn more._

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/50ad74c7-0366-4aea-8929-de02fd4be4c0" alt="SummarEase Screenshot 1" width="48%">
  <img src="https://github.com/user-attachments/assets/54f3faa2-3be2-4ce8-903e-02a16520d24c" alt="SummarEase Screenshot 2" width="48%">
</p>

## Features

- **Smart Summarization** — Get comprehensive or concise summaries powered by Generative AI.  
- **Interactive Q&A** — Ask any question about your document and get context-aware answers.  
- **Reference-Linked Summaries** — See exactly where in the document each summary point comes from.  
- **Quiz Generation** — Automatically generate quizzes to test your understanding of the PDF content.  
- **Integrated PDF Viewer** — View and explore extracted text from uploaded PDFs.  
- **Export Options** — Download summaries, Q&A history, and more in various formats.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
# 1️⃣ git clone https://github.com/<your-username>/SummarEase.git
cd SummarEase
pip install -r requirements.txt

# 3️⃣ Create a .env file in the project root and add your Gemini API key
echo GEMINI_API_KEY="YOUR_GEMINI_API_KEY_HERE" > .env

# 4️⃣ Run the Streamlit app
streamlit run main.py

