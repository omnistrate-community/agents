# Omnistrate Platform MCP Agents

This repository contains specialized agents for the Omnistrate platform, designed to work with the omnistrate-platform MCP (Model Context Protocol) server.

## Overview

These agents provide expert guidance, integration support, and operational assistance for working with the Omnistrate platform. Each agent leverages the omnistrate-platform MCP server to access official documentation, API references, and platform best practices.

## Available Agents

### omnistrate-expert
Specialist for Omnistrate platform integration, documentation search, and platform operations.

**Key Capabilities:**
- Documentation search and reference using omnistrate-platform MCP
- Platform integration and configuration guidance
- API implementation assistance
- Troubleshooting platform-specific issues
- Architecture design with platform-native patterns
- Operational best practices and optimization

**Requirements:**
- omnistrate-platform MCP server must be configured and available
- The agent operates exclusively through the MCP server for all platform operations

## Usage

Each agent is defined in a markdown file in the `agents/` directory. These agents are designed to be used with Claude Code or other AI systems that support the MCP protocol.

### Agent Format

Each agent specification includes:
- **Frontmatter**: Metadata including name, description, category, and required MCP servers
- **Purpose**: Clear description of the agent's role and capabilities
- **Requirements**: Critical requirements and dependencies
- **Triggers**: Conditions that activate the agent
- **Behavioral Mindset**: How the agent approaches tasks
- **Key Actions**: Specific actions the agent can perform
- **Workflow Patterns**: Common usage patterns and examples
- **Boundaries**: What the agent will and won't do

## Requirements

### MCP Server Configuration

The agents in this repository require the omnistrate-platform MCP server to be configured. Ensure that:

1. The MCP server is installed and accessible
2. Authentication credentials are properly configured
3. The MCP server is listed in your Claude Code or AI system configuration

## Contributing

To add a new agent:

1. Create a new markdown file in the `agents/` directory
2. Follow the existing agent format for consistency
3. Include complete frontmatter with name, description, category, and required MCP servers
4. Document all capabilities, requirements, and boundaries
5. Provide workflow patterns and examples

## License

Apache License 2.0 - See LICENSE file for details
