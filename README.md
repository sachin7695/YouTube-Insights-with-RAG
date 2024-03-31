# Building a RAG application for YouTube insights 

Repository showcasing a user-friendly implementation of a Retrieval-Augmented Generation (RAG) application using Pinecone and OpenAI's API. Empower your projects with advanced natural language processing capabilities by easily integrating this solution to extract insights from YouTube videos through simple Q&A interactions.
## Setup

1. Create a virtual environment and install the required packages:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

2. Create a free Pinecone account and get your API key from [here](https://www.pinecone.io/).

3. Create a `.env` file with the following variables:

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
PINECONE_API_KEY = [ENTER YOUR PINECONE API KEY HERE]
PINECONE_API_ENV = [ENTER YOUR PINECONE API ENVIRONMENT HERE]
```
4. Libraries used openai 
```langchain
langchain-openai
langchain_pinecone
langchain[docarray]
docarray
pydantic==1.10.8
pytube 
python-dotenv
tiktoken 
pinecone-client 
scikit-learn
ruff
git+https://github.com/openai/whisper.git
```
   
