# MultiPDF-LLM-Chatbot

## Description:

This Streamlit application empowers you to have a conversation-like interaction with the content of your PDF files. It leverages cutting-edge large language models (LLMs) from Google Generative AI to provide comprehensive answers to your questions about the uploaded PDFs.

## Features:

- Upload multiple PDF files for processing.
- Ask questions in a natural, conversational style.
- Receive detailed answers extracted from the uploaded PDFs.
- "Answer not available in the context" message for improved accuracy.

## Requirements:

- Python 3.10 (with required libraries)
- Streamlit ([https://streamlit.io/](https://streamlit.io/))
- PyPDF2 ([https://pypi.org/project/PyPDF2/](https://pypi.org/project/PyPDF2/))
- langchain ([https://github.com/langchain-ai/langchain](https://github.com/langchain-ai/langchain))
- langchain-community ([https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop](https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop))
- langchain-google-genai ([https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop](https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop))
- dotenv ([https://pypi.org/project/python-dotenv/](https://pypi.org/project/python-dotenv/))
- A Google Cloud project with a Generative AI API key ([https://cloud.google.com/ai/generative-ai](https://cloud.google.com/ai/generative-ai))

## Installation:

1. Create a virtual environment.
2. Install required libraries using `pip install -r requiremenrs.txt`.
3. Obtain a Google Cloud project and Generative AI API key ([https://cloud.google.com/ai/generative-ai](https://cloud.google.com/ai/generative-ai)).
4. Create a `.env` file in your project's root directory with the following line: `GOOGLE_API_KEY=<YOUR_API_KEY>`.

Usage:

1. Clone this repository or download the code.
2. Run the application using `streamlit run app.py`.
3. Upload your PDF files and ask questions in the text input field.
4. Click "Submit & Process" after uploading for initial indexing.
