# Health-Tracker
Health Tracker
## Vedio Reference



https://github.com/user-attachments/assets/ea1c756c-f64c-4d78-b93b-3f9ca3a5e341


# 🏥 Patient Health Care Monitor: AI-Driven Patient Journey & Risk Analytics Platform
This repository contains the development notebooks for the Patient Health Care Monitor project, created for the ArangoDB Hackathon: **"Building the Next-Gen Agentic App with GraphRAG & NVIDIA cuGraph."**

## 🏆 Hackathon Submission
This project is our submission for the ArangoDB Hackathon on Devpost, where we've created an agentic healthcare application integrating GraphRAG and GPU-accelerated graph analytics with NVIDIA cuGraph.

🔗 **Hackathon Link:** [Building the Next-Gen Agentic App with GraphRAG & NVIDIA cuGraph](https://arangodbhackathon.devpost.com/?_gl=1*125dmf4*_gcl_au*OTc3NTI1NzY3LjE3NDE0NTU4NjA.*_ga*MTI2NDQwNzc1OS4xNzQxNDU1ODYx*_ga_0YHJK3Y10M*MTc0MTYwNjQ5Ni40LjEuMTc0MTYwNjQ5OS4wLjAuMA..)

## 📊 Project Overview
Patient Health Care Monitor is an AI-powered healthcare platform designed to monitor and analyze patient journeys and health risks using graph-based data models, AI reasoning, and GPU acceleration. The platform enables healthcare professionals to:

✅ Visualize complete patient medical journeys  
✅ Identify high-risk patients through graph analytics  
✅ Discover treatment patterns and correlations  
✅ Query medical data using natural language  
✅ Analyze complex medical relationships with graph algorithms  


## 📓 Repository Contents

1. **STEPS_Patient_Health_Care_Monitor.ipynb**  
   This notebook develops the core platform in step-by-step progression:  
   - **Step 0:** Package installation and environment setup  
   - **Step 1:** Dataset preparation and initial analysis  
   - **Step 2:** Converting and loading graph data into NetworkX with GPU acceleration  
   - **Step 3:** Persisting the graph in ArangoDB  
   - **Step 4:** Building the agentic application with LangChain & LangGraph  
   - **Step 5:** Visualizing the data using Plotly 

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **ArangoDB** | Graph database for storing and querying medical data |
| **NetworkX** | Python library for graph data structures and algorithms |
| **NVIDIA cuGraph** | GPU-accelerated graph analytics |
| **LangChain & LangGraph** | Framework for creating reasoning chains and agentic workflows |
| **Groq AI** | AI model provider for LLM integration |
| **Matplotlib** | Data visualization |

## 🚀 Workflow Overview
```text
Step 0: Package installation and environment setup
   │
   ├── Step 1: Dataset preparation and initial analysis
   │      │
   │      ├── Load patient, disease, and relationship data
   │      ├── Clean and structure the data
   │      └── Handle missing values
   │
   ├── Step 2: Converting and loading graph data into NetworkX with GPU acceleration
   │      │
   │      ├── Create graph structure from data
   │      └── Enable GPU acceleration with cuGraph
   │
   ├── Step 3: Persisting the graph in ArangoDB
   │      │
   │      ├── Store graph in ArangoDB
   │      └── Optimize for querying
   │
   ├── Step 4: Building the agentic application with LangChain & LangGraph
   │      │
   │      ├── Create reasoning chains for medical analysis
   │      └── Integrate LLM for natural language queries
   │
   └── Step 5: Visualizing the data using Plotly
          │
          ├── Generate interactive visualizations
          └── Display patient journeys and medical insights


## 📋 Prerequisites
To run these notebooks, you'll need:

✅ Python 3.8+  
✅ NVIDIA GPU with CUDA support (for maximum performance)  
✅ ArangoDB cloud instance or local installation  
✅ API keys for Groq AI or other LLM provider  


## 🛠️ Installation
Run the following commands to set up the environment:

```bash
# Install nx-arangodb
pip install nx-arangodb

# Install nx-cugraph (if GPU available)
pip install cugraph-cu12 --extra-index-url https://pypi.nvidia.com

# Install LangChain & LangGraph
pip install --upgrade langchain langchain-community langchain-openai langgraph 

# Install langchain_groq
pip install langchain_groq



