# Qdrant Docker Compose

Docker Compose configuration for running [Qdrant](https://qdrant.tech/) vector search engine.

## Quick Start

```bash
docker-compose up -d
```

## Configuration

- Qdrant UI: http://localhost:6333
- REST API: http://localhost:6334

Set `QDRANT_API_KEY` in `.env` file for API key authentication.

## Volumes

- `qdrant_storage` - persistent storage for Qdrant data