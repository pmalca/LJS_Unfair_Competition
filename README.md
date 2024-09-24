# Legal Judgment Simulation for Peruvian Unfair Commpetition Caselaw

## Project Overview

This project is an AI system designed to assist legal professionals by comparing user-submitted facts with a curated database of legal cases. The AI retrieves the most relevant cases using Retrieval-Augmented Generation (RAG) and then leverages a large language model (LLM) to generate a detailed report. The system relies on past cases as the 'ground truth,' using them to inform the AI's reasoning process.

Key features include:
- **Fact Comparison**: Users introduce the facts of a case, and the AI retrieves the most similar legal cases from the curated database.
- **RAG Integration**: The AI combines Retrieval-Augmented Generation techniques with legal case retrieval to provide context for generating reports.
- **Structured Embeddings**: The legal case embeddings follow a specific structure, containing a summary (e.g., the case outcome) and the decision's page, stored as one string.
- **LLM-based Report Generation**: The LLM generates reports that compare the user's case with the retrieved legal cases, offering insights based on existing judicial decisions.
- **Citation Tracking**: The system cites the relevant cases used by the LLM, allowing the user to contrast the AI's conclusions with real legal sources.
  
## Motivation

The project seeks to address a significant gap in the AI and Data Science space, where open and structured databases for legal cases are rare. By making both the database and the code publicly available, we aim to:
- **Reproduce Results**: Allow others to replicate the project and validate its findings.
- **Encourage Innovation**: Provide the foundation for others to develop new methodologies in the field of AI for law.
  
## Framework: Legal Judgment Simulation

This project introduces a new framework for Natural Language Processing (NLP) applied to law: **Legal Judgment Simulation (LJS)**. It mimics the reasoning process of a judge, who must apply laws and prior judgments to similar facts in order to reach a decision.

While the NLP task **Legal Judgment Prediction (LJP)** mostly focuses on predicting outcomes based on facts, **Legal Judgment Simulation (LJS)** goes further by:
- **Comparing Facts**: Applying legal reasoning from similar past cases to new cases.
- **Grounded in Precedents**: Ensuring the generated report is based on real-world judicial decisions.
  
LJS represents the next step in evolving AI-driven legal analysis by not only predicting outcomes but also simulating the legal reasoning process that leads to a decision.

## How It Works

1. **User Input**: The user submits a description of the facts for a particular case.
2. **Case Retrieval**: The system uses RAG to retrieve the most relevant cases from the curated legal database.
3. **LLM Report Generation**: The LLM, armed with the retrieved cases as context, generates a detailed legal report.
4. **Citing Ground Truth**: The report includes citations to the cases used by the LLM, ensuring transparency and enabling the user to verify the sources.
  
## Open-Source Database & Code

The entire database of legal cases, along with the code for this AI system, is open and publicly available. We believe that providing open access to legal case datasets will encourage further research and development in AI for law, which is currently a low-resource area in Data Science.

## Applications

- **Legal Research**: Automate the comparison of legal cases based on facts, retrieving precedents relevant to a case at hand.
- **Judicial Support**: Assist judges and legal professionals by simulating legal reasoning based on past cases.
- **AI-driven Legal Analysis**: Develop a foundation for applying AI models to simulate legal decision-making.

## Conclusion

This project aims to be a groundbreaking step toward improving access to legal resources and providing a solid framework for AI-driven legal reasoning. The Legal Judgment Simulation framework can potentially transform how we use AI to understand, predict, and simulate judicial processes.

## Conclusion

Download the datasets from the following link: https://drive.google.com/drive/folders/1JTZQqmfEnzBlTzz6RH_djocuYylI3d_A?usp=sharing 

