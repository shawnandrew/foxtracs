# MCP Server

We will use [Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk) for developing MCP Servers.

    uv init weather

    uv add "mcp[cli]"

added weather.py dummy server

Test it with the MCP Inspector:

    mcp dev weather.py

    MCP Inspector is up and running at http://localhost:5173 

Open the url in browser: http://localhost:5173

Select Tools Tab and list and run the tool.

Install [Claude Desktop](https://claude.ai/download)

You can install this weather server in Claude Desktop and interact with it right away by running: 

    mcp install weather.py





