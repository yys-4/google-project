# Multi-purpose Notebooks Repository

This repository contains a collection of Jupyter notebooks that demonstrate various machine learning and data scraping techniques.

## Notebooks

### 1. Scrapping with Firecrawl

*   **File:** `Scrapping_with_Firecrawl.ipynb`
*   **Description:** This notebook showcases how to use the Firecrawl library for web scraping. It provides a simple example of how to fetch and parse a web page to extract its main content.

### 2. Art Generation

*   **File:** `artgen.ipynb`
*   **Description:** This notebook is intended for an art generation project. It is currently a skeleton and does not contain any code.

### 3. Local Chatbot with Document Knowledge

*   **File:** `chat_documents_w_python.ipynb`
*   **Description:** This notebook demonstrates how to build a local chatbot that can answer questions about a specific set of documents. It uses the LangChain and Ollama libraries to create a retrieval-augmented generation (RAG) pipeline, allowing you to chat with your documents using a local large language model.

### 4. SynthID Text Watermarking

*   **File:** `notebooks/synthid_text_huggingface_integration.ipynb`
*   **Description:** This notebook explains how to use Google's SynthID to watermark and identify AI-generated text. It shows how to integrate SynthID with models from the Hugging Face Transformers library, apply watermarks to generated text, and detect their presence.

## Getting Started

To run these notebooks, you will need to have Python and Jupyter Notebook installed. You will also need to install the required libraries for each notebook, which are listed at the beginning of each file.

## Usage

1.  Clone this repository:
    ```bash
    git clone https://github.com/yys-4/google-project.git
    ```
2.  Navigate to the repository directory:
    ```bash
    cd google-project
    ```
3.  Install the required dependencies for the notebook you want to run (e.g., for `Scrapping_with_Firecrawl.ipynb`):
    ```bash
    pip install firecrawl-py
    ```
4.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5.  Open the desired notebook and run the cells.