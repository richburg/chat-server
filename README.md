# chat-server
Asynchronous and concurrent TCP chatting server using raw text for communication.

## Configuration
Edit `server/config.py`. The variables are highly self-documented with type annotations.

## Quick Start
Get up and running in seconds:
```bash
python3 -m server
```

## Production Deployment
```bash
docker build -t chat-server .
docker run -p 5000:5000 chat-server
```

## Changelog
### [1.0.0] - 2025-08-24
Hilariously minimal. Open for development.

### [1.0.1] - 2025-08-27
Added kick and list commands.
