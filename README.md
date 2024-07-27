# pdf_chatbot_lanchain
This Streamlit application allows users to upload PDF documents, process their text, and ask questions about the content using Google's Generative AI embeddings and the FAISS vector store.

## Features

- Upload PDFs: Users can upload multiple PDF files.
- Process PDF Text: Extracts text from uploaded PDFs and splits it into chunks for better processing.
- Vector Store Creation: Uses FAISS to create a vector store of the text chunks for efficient similarity search.
- Conversational AI: Utilizes Google's Generative AI for question-answering based on the context of the PDF content.

## Requirements

- Python 3.8+
- Streamlit
- PyPDF2
- LangChain
- FAISS
- Google Generative AI SDK
- Python-dotenv

## Installation

1. Clone the repository: https://github.com/rishabh-jain26/pdf_chatbot_lanchain.git
   cd chat-pdf-gemini
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
GOOGLE_API_KEY=your_google_api_key_here
streamlit run app.py
.
├── app.py
├── .env
├── requirements.txt
├── README.md
└── faiss_index/  # Directory to save the FAISS index

Make sure to replace https://github.com/your-username/chat-pdf-gemini.git with the actual URL of your repository if you plan to host it on GitHub. Also, ensure that your requirements.txt file contains all the necessary dependencies for your project.
