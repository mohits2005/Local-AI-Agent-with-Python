AI-Powered Q&A Assistant for Pizza Restaurant

This project is an AI-powered Q&A assistant designed for a pizza restaurant. It uses LangChain and Ollama LLM (Llama3.2) to provide accurate answers to customer questions based on real reviews.

The system retrieves the most relevant reviews using a retriever module, processes them with a prompt template, and generates context-aware responses through the large language model.

Features

Review-based Q&A: Answers come directly from customer reviews.

LangChain Integration: Combines retriever, prompt templates, and LLM seamlessly.

Interactive CLI: Users can ask questions continuously until they quit.

Customizable: Easily adaptable for other businesses or datasets.

Installation

Clone the repository:

git clone https://github.com/your-username/pizza-qa-assistant.git
cd pizza-qa-assistant


Install dependencies:

pip install langchain_ollama langchain_core


Ensure you have Ollama LLM installed and running with the llama3.2 model.

Usage

Run the script:

python main.py


Then type your questions. Example:

Ask your question (q to quit): What do customers say about the cheese quality?

Project Structure
pizza-qa-assistant/
│-- main.py          # Main script with Q&A logic
│-- vector.py        # Retriever module for fetching relevant reviews
│-- README.md        # Project documentation

Example Output

User Input:

Ask your question: How is the delivery service?


AI Response:

Most customers say the delivery is quick and reliable, often arriving before the estimated time.
