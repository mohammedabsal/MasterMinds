# MasterMinds

## Overview
The Second Mind is an AI-driven system that mimics human learning by iteratively refining ideas through specialized agents. It utilizes **LangGraph** for structured workflows, **Llama (LLM)** for intelligent text generation, and **web data extraction** to enhance research insights.

## Features
- **Multi-Agent System**: Implements six specialized agents (Generation, Reflection, Ranking, Evolution, Proximity, Meta-Review) managed by a Supervisor Agent.
- **LangGraph Workflow**: Coordinates agent interactions efficiently.
- **LLM Integration**: Uses Llama to generate and refine hypotheses.
- **Web Scraping & APIs**: Fetches real-time data to inform decision-making.
- **Memory System**: Stores and recalls past interactions for continuous improvement.
- **Flask API & Optional React UI**: Allows easy interaction and visualization.

## Tech Stack
- **Backend**: Python, LangGraph, Flask
- **AI Models**: Llama LLM
- **Data Extraction**: BeautifulSoup, Requests
- **Storage**: SQLite / Firebase (for interaction memory)
- **Frontend (Optional)**: React, Axios

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/the-second-mind.git
   cd the-second-mind
   ```
2. Install dependencies:
   ```bash
   pip install flask beautifulsoup4 requests pandas langgraph
   ```
3. Run the Flask backend:
   ```bash
   python app.py
   ```
4. (Optional) Start the React frontend:
   ```bash
  
   ```

## Usage
- Send a query to the backend to process ideas and retrieve enhanced insights.
- View agent interactions and results via API responses or the web UI.

## Contributing
Feel free to submit issues, pull requests, or suggestions!

## License
This project is licensed under the MIT License.

