# mcp-sample-ts

A TypeScript MCP (Model Context Protocol) server that provides weather forecast data using the [National Weather Service API](https://api.weather.gov).

## Tools

- **get_forecast** — Returns a weather forecast for a given latitude/longitude (US locations only).

## Setup

```bash
npm install
npm run build
```

## Usage

Run the server via stdio transport:

```bash
node dist/index.js
```

## Requirements

- Node.js >= 18
- TypeScript >= 6
