# Garmin Connect MCP server

based on [garth](https://github.com/matin/garth)

## Install

```json
{
  "mcpServers": {
    "Garth - Garmin Connect": {
      "command": "uvx",
      "args": [
        "garth-mcp-server"
      ],
      "env": {
        "GARTH_TOKEN": "<output of `uvx garth login`>"
      }
    }
  }
}
```

Make sure the path for the `uvx` command is fully scoped as MCP doesn't
use the same PATH your shell does. On macOS, it's typically
`/Users/{user}/.local/bin/uvx`.

## Usage

![image](https://github.com/user-attachments/assets/91581e3f-327e-4b01-9d8b-4fdb1f8e58fe)
