## Features

- AI-powered agent chat and automation
- Extensible with Docker and async capabilities
- Environment-based configuration

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Environment Variables

Copy `.env.example` to `.env` and fill in your secrets:

```bash
cp .env.example .env
```

## Usage

You can start by running the Jupyter notebook:

```bash
jupyter notebook DSA_solver.ipynb
```

Or use the Python modules as needed for your automation tasks.

## Dependencies

- autogen-agentchat
- autogen-core
- autogen_ext
- autogen-ext[docker]
- asyncio
- dotenv
- openai
- tiktoken
