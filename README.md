# Data_analyzer_Agent
This project demonstrates an intelligent agent system that routes user queries to the most suitable data tool using GPT-4o-mini with function calling. The system acts as a Router that interprets the user's intent and dynamically chooses the appropriate backend service to handle the request.

 System Architecture
The architecture includes the following components:

User: Initiates requests in natural language (e.g., "Show me last month's sales", "Analyze trends", etc.).

Router (GPT-4o-mini w/ function calling): Acts as a smart dispatcher. It parses the user's intent and calls the correct function/tool to respond accurately.

Tools:

 Look Up Sales Data Tool – Retrieves specific sales records or metrics.

 Data Analysis Tool – Performs statistical or trend analysis on datasets.

 Data Visualization Tool – Generates charts or graphs for easy visual interpretation.

The flow is fully autonomous: the router decides which tool to invoke, executes the function, and returns the result to the user in a natural, conversational format.
