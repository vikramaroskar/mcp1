# mcp1
creating an mcp poc


code $env:AppData\Claude\claude_desktop_config.json
this is documentation path - doesn't work, need the below path for woroking

C:\Users\vikra\AppData\Roaming\Claude\claude_desktop_config.json


{
    "mcpServers": {
        "weather": {
            "command": "node",
            "args": [
                "C:\\Users\\vikra\\github\\mcp1\\src\\build\\index.js"
            ]
        }
    }
}


npm run build  
- to generate build\index.ts


to run MCP server in command line we can run manually
C:\Users\vikra\github\mcp1>node build\index.js
