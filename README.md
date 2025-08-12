[Email](mailto:ahmadi.naser68@gmail.com) | [LinkedIn](https://www.linkedin.com/in/naser-ahmadi-ab028419a/) | [Github](https://github.com/naserahmadi)

---

I'm a Data Scientist with a PhD in Artificial Intelligence from Sorbonne University, specializing in NLP. I focus on applying state-of-the-art technologies like transformers across a range of NLP tasks, including chatbots, question answering, and summarization. I also work on graph analysis, knowledge graphs, and other areas of data science, bringing together academic research and hands-on experience.

---

## Education
- **Ph.D., Data Science** | Sorbonne University (_Jan 2022_)
- **M.S., Computer Engineering**	| The University of Tehran (_Sep 2016_)
- **B.S., Computer Engineering** | Shiraz University of Technology (_Sep 2012_)

---

## Work Experiences
**NLP Data Scientist @ OKRA, Leiden (_Jan2025_ - _Present_)**
- Implemented advanced NLP solutions such as summarization and semantic search for medical data,
using LLMs.
- Developed a RAG-based question answering system, combining expert insights from medical records.

**Postdoc @ Aarhus University, Aarhus (_Aug 2024_, _Jan 2025_)**
- Led a six-month research project on leveraging LLMs for systematic literature reviews in software engineering.
- Created a comprehensive data set of 100 research papers and applied advanced LLM techniques, including
Chain-of-Thought (COT), Self-consistency, and retrieval-augmented generation (RAG) methods.

**Lead Data Scientist @ SystemGroup, Tehran (_Mar 2024_ - _Aug 2024_)**
- Led design and development of a digital assistant featuring QA and report generation capabilities.
- Engineered RAG-based QA system and Text2SQL model, fine-tuning open-source LLMs for Persian
language queries.
- Created comprehensive training and testing datasets, driving accuracy and reliability of the digital
assistant.

**Lead Data Scientist @ Hamrah-e-Avval (MCI), Tehran (_Jan 2022_ – _Mar 2024_)**
- Continual pre-training of open source LLMs to enhance Persian language understanding.
- Developed a production-grade FAQ chatbot managing interactions with 1 million monthly users.
- Led design of a knowledge graph for a Persian search engine, enabling natural language queries with
real-time infobox generation, serving 100 queries per second.
- Improved search systems by implementing advanced NLP methods using mBART and mT5, increasing
search efficiency and user satisfaction.

**Part-time Data Scientist @ KPMG, Berlin (_Oct 2018_ – _Jan 2022_)**
- Created an Audit Knowledge graph
- Worked on relation extraction in structured documents
- Developed methods for Text to Structured Text Matching
- Implemented topic modeling for audit texts

---

## Projects

### LLM Systematic Literature Review
<div style="display: flex; align-items: center;">
  <div style="flex: 1; padding-right: 20px;">
    <img alt="image" src="https://github.com/user-attachments/assets/8e16397c-b68e-429f-ba65-702afeafe19f" style="width: 100%;" />
  </div>
  <div style="flex: 2;">
    I led a six-month research project focused on leveraging large language models (LLMs) for automating and enhancing systematic literature reviews (SLRs) in the field of software engineering. The project aimed to evaluate the capabilities of LLMs in identifying, synthesizing, and reasoning over academic content, using a curated dataset of 100 peer-reviewed research papers. We explored a range of advanced prompting and inference techniques—including Chain-of-Thought (CoT), Self-Consistency, and Retrieval-Augmented Generation (RAG)—to assess their effectiveness in various stages of the SLR pipeline.
    <br><br>
    To systematically evaluate model performance, we designed a series of controlled experiments that varied key parameters such as model type, prompting strategy, and retrieval method. These experiments were used to measure the accuracy, consistency, and comprehensiveness of the generated outputs in relation to human-annotated baselines. The study provided valuable insights into the strengths and limitations of LLMs for evidence synthesis, offering a promising step toward semi-automated or fully automated SLR workflows in research.
  </div>
</div>

### A Text2SQL LLM model
I led the design and development of a Persian-language digital assistant equipped with advanced report generation capabilities. A core component of this assistant was a custom-engineered Text2SQL module, which translated natural language queries into executable SQL commands. To support this, I fine-tuned open-source LLMs to understand and process Persian-language inputs in structured data contexts, enabling seamless interaction with underlying databases.
<br><br>
In parallel, I created comprehensive training and testing datasets tailored to Persian query patterns and schema variations, ensuring high accuracy and robustness of the system. These efforts resulted in a reliable digital assistant capable of answering data-driven questions and generating dynamic reports in natural language, significantly improving user access to structured information in Persian.

### A FAQ bot for ERP clients 
<div style="display: flex; align-items: center;">
  <div style="flex: 2; padding-right: 20px;">
    I engineered a Retrieval-Augmented Generation (RAG)-based question answering system tailored for Persian-language queries by fine-tuning open-source large language models (LLMs). This hybrid architecture combined dense retrieval with generative response capabilities, allowing the system to ground its answers in relevant context retrieved from a curated Persian knowledge base.
    <br><br>
    To ensure the system’s effectiveness, I created comprehensive training and evaluation datasets that reflected a wide range of real-world Persian queries. These datasets were carefully designed to capture diverse linguistic patterns and were validated to ensure quality and coverage. The resulting RAG-based assistant demonstrated high accuracy and contextual relevance, making it a reliable tool for open-domain question answering in Persian.
  </div>
  <div style="flex: 1;">
    <img alt="image" src="https://github.com/user-attachments/assets/19d7b130-689c-472e-ab26-5baf225bf949" style="width: 100%;" />
  </div>
</div>

### A RAG-based for customer support
In this project, I developed an advanced Retrieval-Augmented Generation (RAG) Chatbot that integrates a Knowledge Base (KB) with a powerful Large Language Model (LLM). The implementation leveraged Ollama and Langchain for LLM calling and KB implamantations. I applied prompt engineering techniques to improve the quality of interactions with the LLM, ensuring the chatbot's responses were coherent and precise. I incorporated a re-ranker mechanism that prioritizes the most pertinent information from the Knowledge Base before generating the final response. The project also employed a Vector Database (ChromaDB) to efficiently manage and retrieve high-dimensional data, crucial for the real-time processing capabilities of the chatbot. 
<br>
<img alt="Picture1" src="https://github.com/naserahmadi/naserahmadi.github.io/assets/45039751/f4908556-968a-4827-a063-4032bb0c1c8d" style="width: 100%;" />

### ALLEF: A Large Language Model for Farsi
I contributed to the development of ALLEF, a large language model (LLM) for Persian, by performing continual pre-training on LLaMA-1 and LLaMA-2 models to improve their understanding of the Persian language. The process began with the creation of a high-quality Persian corpus, which involved collecting large-scale text data from diverse sources, cleaning, normalizing, and deduplicating it to ensure both linguistic richness and consistency. We extended the tokenizer to better handle Persian morphology and vocabulary before initiating continual pre-training on the prepared corpus.
<br><br>
Following the language modeling phase, we conducted instruction fine-tuning to align the model with user-intent tasks such as question answering, summarization, and classification. To support this, we designed and annotated a Persian instruction dataset, with native speakers verifying both the training and test splits for quality and relevance. This pipeline significantly improved the model’s performance in downstream NLP tasks, positioning ALLEF as a foundational LLM for high-quality Persian-language applications.
<br>
<img alt="image" src="https://github.com/naserahmadi/naserahmadi.github.io/assets/45039751/cc85a7d9-d23a-4f0b-8180-1750c4ded8c8" style="width: 100%;" />

### Multi Text Summarization
I designed and implemented a multi-text summarization pipeline to generate concise, query-focused summaries from multiple retrieved documents. After identifying the most relevant text chunks using semantic embeddings—computed during the retrieval phase for a given query—the system aggregated these chunks and passed them to a fine-tuned mBART model specifically trained for summarization in Persian.
<br><br>
This allowed the system to produce coherent and context-aware summaries that distilled key information from multiple sources into a single, unified response. The approach was particularly effective for queries requiring information synthesis across diverse documents, enhancing the user’s ability to grasp the core message without reading through each page. This summarization module complemented the QA and infobox components, providing a more comprehensive and intelligent search experience.
<br>
<img alt="image" src="https://github.com/naserahmadi/naserahmadi.github.io/assets/45039751/6a851077-7bdf-4bae-878c-297feacfbfc9" style="width: 100%;" />

### Question Answering
I developed an extractive question answering (QA) system tailored for Persian by fine-tuning an XLM-RoBERTa model on domain-specific QA datasets. The goal was to enhance user interaction by highlighting the most relevant text spans directly within the top-ranked search results. For each natural language query, the system retrieved a ranked list of relevant documents using semantic search, then applied the fine-tuned QA model to extract the most probable answer spans from those documents.
<br><br>
This approach enabled users to quickly identify the information they were seeking without needing to open each result individually. The system integrated seamlessly with the search engine, displaying highlighted answers within snippets of the top results, significantly improving the search experience by making it more informative and efficient. The multilingual capabilities of XLM-RoBERTa also ensured better generalization across diverse Persian language sources.
<br>
<img alt="image" src="https://github.com/naserahmadi/naserahmadi.github.io/assets/45039751/198d934e-4f91-47c8-af04-6cedb76ccb6a" style="width: 100%;" />

### A Persian Knowledge graph
I led the design and development of a knowledge graph (KG) powering a Persian-language search engine, enabling users to issue natural language queries and receive real-time infoboxes alongside relevant news updates. The system was built to serve over 100 queries per second with low latency. I fine-tuned a BERT-based language model on Persian text for semantic search, allowing the system to understand user intent and retrieve relevant entities from the KG. Vespa was used as the vector database for fast similarity search over embedded queries.
<br><br>
The KG itself was constructed by crawling and processing structured and unstructured content from Persian Wikipedia and the broader Persian web. Entities, relationships, and factual attributes were extracted and stored in a versioned format within Cassandra for fast retrieval. Additionally, I implemented a news extraction pipeline that continuously crawled Persian news websites to link the most recent articles to their corresponding entities in the KG. On each user query, the system returned both the entity infobox and a curated list of the most recent news, enabling a dynamic and informative search experience in Persian.
<br>
<img alt="image" src="https://github.com/naserahmadi/naserahmadi.github.io/assets/45039751/1aa1af84-fcca-4a4c-afd9-083bddf5dd80" style="width: 100%;" />

---

## Technical Skills

**Skills:** Agile Methodologies, AI, Machine Learning, Deep Learning, NLP, Knowledge Graphs, Graph Neural Networks, Data Analysis, Version Control (GIT), Docker, FastAPI, Flask, Python, Java, SQL, SPARQL

**Technologies:** Pytorch, Transformers, Datasets, DeepSpeed, Pytorch Lightning, RAG, PEFT, LangChain, OpenAI, Polars, Numpy, Scikit-learn, OLLAMA, Nebula Graph

---

## Publications ([Scholar](https://scholar.google.com/citations?user=wk5Hb14AAAAJ&hl=en))

- **PhD Thesis**: A framework for the continuous curation of a knowledge base system.
- **Building A Knowledge Graph for Audit Information**, EDBT/ICDT 2022.
- **Unsupervised Matching of Data and Text**, ICDE 2022.
- **Wikidata logical rules and where to find them**, Wiki Workshop 2021.
- **RuleBERT: Teaching Soft Rules to Pre-Trained Language Models**, EMNLP 2021.
- **Mining expressive rules in knowledge graphs**, JDIQ 2020.
- **Rulehub: A public corpus of rules for knowledge graphs**, JDIQ 2020.
- **Explainable Fact Checking with Probabilistic Answer Set Programming**, TTO 2019.
