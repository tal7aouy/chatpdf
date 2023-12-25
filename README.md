# PDF Chat App

## Introduction
PDF Chat App is a Streamlit-based web application that allows users to interactively chat with a PDF document. Utilizing advanced NLP techniques and the OpenAI language model, this app extracts text from uploaded PDFs and provides answers to user queries based on the PDF content.

## Features
- **PDF Upload**: Users can upload PDF documents to be processed.
- **Interactive Q&A**: Post upload, users can ask questions and receive answers based on the PDF content.
- **Progress Indicators**: Visual feedback during PDF processing for a better user experience.
- **Collapsible Answer Format**: Answers are displayed in an organized, collapsible format.

## Technologies Used
- [Streamlit](https://streamlit.io/): An open-source app framework for Machine Learning and Data Science projects.
- [LangChain](https://python.langchain.com/): A Python library for building language model applications.
- [OpenAI](https://platform.openai.com/docs/models): Large language models for answering queries.

## Installation
To run this app locally, you need to have Python installed on your system. Follow these steps:

1. **Clone the Repository**
   ```bash
   git clone git@github.com:tal7aouy/chatpdf.git
   cd chatpdf
    ````

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Environment Setup**
- Create a `.env` file in the project root.
- Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`.

4. **Run the App**

```bash
streamlit run app.py
```
## Usage
1. **Launch the App**: Open the local URL provided by Streamlit.
2. **Upload PDF**: Use the 'Upload your PDF' button to select a file.
3. **Query Input**: Type your questions about the PDF content.
4. **View Answers**: Expand the 'See Response' section for the app's responses.

## Contributions
Contributions are welcome. Please adhere to the project's guidelines and code of conduct when contributing.

## License
This project is licensed under the [MIT License](LICENSE).
