# Spring AI MCP Spring

Spring Integration module for Model Control Protocol (MCP) that provides Spring-specific functionality for working with MCP clients.

## Overview

The `spring-ai-mcp` module is part of the [Spring AI MCP](https://github.com/spring-projects-experimental/spring-ai-mcp) project. It provides Spring Framework integration for the Model Control Protocol (MCP), enabling seamless integration of MCP functionality within Spring applications.

## Features

- Spring integration for MCP clients
- Function callback implementation for tool invocations
- Seamless integration with Spring AI's function calling capabilities

## Main Components

### McpFunctionCallback

The `McpFunctionCallback` class is the primary component of this module. It implements Spring AI's `FunctionCallback` interface and provides:

- Integration between Spring AI's function calling system and MCP tools
- Automatic conversion between JSON and Java objects for tool arguments
- Synchronous tool execution support


## Usage

To use this module, add the following dependency to your Maven project:

```xml
<dependency>
    <groupId>org.springframework.experimental</groupId>
    <artifactId>spring-ai-mcp</artifactId>
    <version>0.4.0-SNAPSHOT</version>
</dependency>
```

## License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Links

- [GitHub Repository](https://github.com/spring-projects-experimental/spring-ai-mcp)
- [Issue Tracker](https://github.com/spring-projects-experimental/spring-ai-mcp/issues)

## Contributing

This is an experimental Spring project. Contributions are welcome! Please refer to the main project's contribution guidelines.
