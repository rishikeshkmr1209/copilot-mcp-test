# GitHub Copilot MCP Workshop Instructions

This document provides essential guidance for AI coding agents working in this workshop project.

## Project Overview

This is a workshop project focused on GitHub Copilot Model Context Protocol (MCP) integration. The project demonstrates how to set up and use MCP servers for enhanced AI coding assistance.

## Key Components

### MCP Server Configuration

The project uses a GitHub MCP server configured in `.vscode/mcp.json`:

```json
{
    "servers": {
        "github-mcp-server": {
            "url": "https://api.githubcopilot.com/mcp/",
            "type": "http"
        }
    }
}
```

This configuration enables direct communication with GitHub's Copilot MCP services.

## Development Environment

### Prerequisites
- Visual Studio Code with GitHub Copilot extension
- Access to GitHub Copilot MCP services

### Project Structure
- `.vscode/` - Contains VS Code specific configurations
- `.github/` - Houses GitHub-related configurations and documentation

## Best Practices

1. **MCP Server Integration**
   - Always verify MCP server connectivity before making changes
   - Use the configured GitHub MCP server endpoint for AI-assisted operations

2. **Documentation**
   - Maintain clear documentation of MCP-related configurations
   - Document any custom MCP server implementations or modifications

## Common Operations

This section will be expanded as more workshop content and operations are added to the project.

---

*Note: This is a living document. As the workshop evolves, these instructions will be updated to reflect new patterns and best practices.*