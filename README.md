# LangGraph

LangGraph is a low-level, controllable framework that's built on top of LangChain. It's used to create agent and multi-agent workflows, and is suitable for enterprise-level applications.
This repository contains projects and concepts that showcase the power of LangGraph.

# How it works

LangGraph uses Directed Cyclic Graphs (DCGs) to orchestrate how different components in an AI system interact. A graph in LangGraph is made up of nodes (representing functions or tools) and edges (representing connections between those nodes). 

## Features

**LangGraph** offers advanced functionality, including:

- **Cycles**: LangGraph allows you to define flows that involve cycles, which are essential for most agentic architectures.
- **Persistence**: LangGraph includes built-in persistence, enabling advanced human-in-the-loop and memory features.
- **Human-in-the-loop**: You can interrupt graph execution to approve or edit the next action planned by the agent.
- **Streaming support**: You can stream outputs as they are produced by each node.

## Getting Started

### Prerequisites

To run the projects in this repository, you need the following:

- Python 3.8 or above
- A `.env` file containing the required API keys

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/langgraph.git
   cd langgraph

2. **Create a `.env` file** in the root directory and add the following API keys:

   `WEATHER_API_KEY=`
   `TAVILY_API_KEY=`
   `GROQ_API_KEY=`
   `ASTRA_DB_APPLICATION_TOKEN=`
   `ASTRA_DB_ID=`
   `HUGGINGFACEHUB_API_TOKEN=`
   `GOOGLE_API_KEY=`
   `LANGCHAIN_PROJECT=`
   `LANGCHAIN_API_KEY=`
   `SERPER_API_KEY=`
   `OPENAI_API_KEY=`
   `OPENWEATHERMAP_API_KEY=`

   Replace the placeholders with your actual API keys. You can include only the API keys for the services you wish to use.

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
