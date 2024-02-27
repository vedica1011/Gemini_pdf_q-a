# Chat PDF

This is a Streamlit web application that allows users to interactively ask questions from PDF files using Chat with PDF feature fused with Gemini.

## Usage
1. **Ask a Question**: Enter your question in the text input box provided.
2. **Upload PDF Files**: Upload one or more PDF files containing the relevant information.
3. **Submit & Process**: Click the button to submit the uploaded PDF files and start the processing.

## Features
- **PDF Processing**: Extract text from uploaded PDF files and split it into manageable chunks for processing.
- **Question Answering**: Chat with PDF feature to generate answers to user questions based on the context from PDF files.
- **Interactive Interface**: User-friendly interface for asking questions and viewing responses.

## Setup
1. **Environment Setup**: Make sure to install the required Python packages specified in the `requirements.txt` file.
2. **API Key**: Set up your Google API key and save it in a `.env` file with the variable name `GOOGLE_API_KEY`.
3. **Run the Application**: Run the `main.py` script to launch the Streamlit web application locally.

## Dependencies
- Streamlit
- PyPDF2
- langchain
- google-generativeai
- dotenv

## Credits
- This application utilizes Deloitte's Chat with PDF feature and Google's Gemini model for question answering.
- Developed by [Your Name] for [Your Organization].

