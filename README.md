# Building Multimodal Search and RAG

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRQpDShW0U5T45x11LG2eaDtzFA0YPHu213A&usqp=CAU)

**Retrieval-Augmented Generation (RAG)** is a natural language processing (NLP) technique that improves the output of large language models (LLMs) by using external knowledge sources. RAG combines retrieval- and generative-based AI models to generate responses that are more accurate and context-aware. RAG can be used to improve the effectiveness of LLM applications, such as chatbots and Q&A systems, that need to provide up-to-date information or domain-specific knowledge. 
RAG works by retrieving relevant data or documents in response to a question or task and using them as context for the LLM. This allows the LLM to access real-time data and overcome the limitations of its parametric memory. RAG models can then process and consolidate this knowledge to create unique answers, instructions, or explanations in human-like language. 
RAG can be implemented in Azure Machine Learning using a prompt flow, and it doesn't require a data center. On a PC equipped with NVIDIA RTX GPUs, users can link to private knowledge sources, such as emails, notes, or articles, to improve responses while keeping their data, prompts, and responses secure. 

**What is a contrastive loss?**

Contrastive loss is a metric learning loss function as it calculates the Euclidean distance or cosine similarity between vector pairs. It then assigns a loss value based on a predefined margin threshold. If the distance between two vectors is less than the margin threshold, the loss value is zero.

Triplet loss requires three inputs (anchor, positive, and negative), whereas contrastive loss requires only two (positive and negative) inputs.

Contrastive learning allows models to extract meaningful representations from unlabeled data. By leveraging similarity and dissimilarity, contrastive learning enables models to map similar instances close together in a latent space while pushing apart those that are dissimilar.

![](https://images.app.goo.gl/C8tgVifRp5aNU8DP9)

**Weaviate** is an open-source vector database that uses AI to help developers build AI-powered applications. It's a flexible platform that combines keyword and vector search with machine learning (ML) models to deliver fast, relevant, and contextual search results. 
Weaviate's features include:

- Fast queries: Weaviate can perform nearest neighbor (NN) searches of millions of objects in less than 100 milliseconds.
  
- AI models: Weaviate makes it easy to use state-of-the-art AI models.
  
- Scalability: Weaviate is cloud-native, distributed, and scales with workloads.
  
- Ease of use: Weaviate is easy to integrate with current architecture and has full CRUD support.
  
Weaviate's ecosystem is designed to allow users to build and test applications for free, with the option to choose a plan for production when ready. 
