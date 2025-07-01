## Week 7: Retrieval-Augmented Generation (RAG)

### What is RAG?

**Retrieval-Augmented Generation (RAG)** is a hybrid approach that combines **retrieval-based methods** with **generative language models**. Rather than relying solely on pre-trained internal knowledge, a RAG system retrieves relevant documents from an external knowledge source and uses them as context to generate more accurate and grounded responses.

---

### Applications of RAG

- Open-domain Question Answering – Retrieve facts and generate fluent answers  
- Document Summarization – Summarize content with real-time or external references  
- Chatbots – Enhance reasoning with grounded evidence  
- Medical & Legal Assistants – Reference up-to-date documents for critical domains  

---

### Learning Resources

#### Conceptual Understanding
- [What is RAG? (YouTube – 5 min Intro)](https://www.youtube.com/watch?v=T-D1OfcDW1M)  
- [RAG Overview and Explanation (Playlist Video)](https://www.youtube.com/watch?v=X0btK9X0Xnk&t=3184s)  

#### Hands-On Implementation
- [RAG Implementation Tutorial (YouTube)](https://www.youtube.com/watch?v=J5_-l7WIO_w&t=4s)  
- [Implement RAG using Gemini + LangChain (YouTube)](https://www.youtube.com/watch?v=uus5eLz6smA)  
  Learn how to integrate Google Gemini API with LangChain to build a full RAG pipeline using document loaders, embeddings, vector stores, and Gemini-generated responses.  
  Note: You can also use Google Colab instead of setting up a local `conda` environment.

---

## Milestone 5  
### IITB UG Rule Assistance Bot

Create a chatbot that answers queries about IIT Bombay’s UG academic rules using Gemini and RAG.  
It fetches relevant sections from the UG rulebook and circulars, then generates helpful, student-friendly responses.

- Host the chatbot using Node.js or any suitable backend framework  
- Add a GIF demo of the working chatbot and deployed site in your GitHub README

---
