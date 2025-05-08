MCP Server Basic Example
This is a basic example of a Model Context Protocol (MCP) server implementation that demonstrates core functionality including tools and resources.

Setup Steps
Initialize the project (Go to any local folder and launch powershell or cmd):



uv init mcp-server-basic


cd mcp-server-basic



Create virtual environment and activate it
  uv venv
  
  .venv\Scripts\activate

  
Install dependencies:


uv add "mcp[cli]"
or



uv add -r requirements.txt

Running the Server

To run the server with the MCP Inspector for development:

uv run mcp dev main.py

To run the server normally:


uv run mcp run
To install the server in Claude desktop app:

uv run mcp install main.py
