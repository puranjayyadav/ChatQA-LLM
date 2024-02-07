# ChatQA PDF Chat Application

## Overview

ChatQA is a cutting-edge chat application designed to enhance the user experience in interacting with PDF documents. Developed between December 2023 and January 2024, it leverages the powerful capabilities of LangChain to provide a seamless interface for querying and understanding content within PDFs. This application stands out by incorporating advanced techniques like semantic search and Retrieval-Augmented Generation (RAG) to deliver precise and contextually relevant answers.

## Key Features

### Semantic Search with Retrieval-Augmented Generation

- **Implementation Date:** Dec 2023 - Jan 2024
- Utilizes embeddings to perform semantic searches across PDF contents, ensuring highly relevant and context-aware results.
- Enhances the chat experience by dynamically generating responses that are informed by the content of PDFs.

### Embeddings Storage

- **Vector Databases:** ChromaDB and Pinecone
- Embeddings generated from the PDF contents are stored in state-of-the-art vector databases, ChromaDB and Pinecone, facilitating fast and efficient retrieval.

### Distributed Processing

- **Technologies:** Celery and Redis
- To maintain optimal performance and handle high user loads, ChatQA employs distributed processing. This setup ensures scalability and responsiveness of the semantic search and text generation features.

### User Interaction Tracing

- Tracing mechanisms are integrated to gain insights into how users interact with the text generation features. This data is invaluable for continuous improvement and user experience enhancement.

### Server-to-Browser Text Streaming

- ChatQA extends LangChain to implement a novel server-to-browser text streaming feature. This allows for real-time interaction with the PDF content, significantly enhancing user engagement.

## Technologies Used

- **LangChain:** A powerful library for building applications with language models.
- **ChromaDB & Pinecone:** Vector databases for efficient storage and retrieval of embeddings.
- **Celery & Redis:** Used for distributed task processing to ensure the application scales well under load.
- **Tracing:** For monitoring user interactions and improving the system.

## Getting Started

To get started with ChatQA, ensure you have the following prerequisites installed:

- Python 3.8+
- Redis
- Docker (for ChromaDB and Pinecone services)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-repository/ChatQA.git
