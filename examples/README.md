# OpenAI Node.js SDK Examples

This directory contains standalone, runnable TypeScript and JavaScript examples demonstrating how to use the OpenAI Node SDK across various API endpoints and integrations.

## Prerequisites

Set your OpenAI API key in your environment:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

For Azure OpenAI or AWS Bedrock examples, provide the relevant provider credentials as documented inside those specific scripts.

## Running Examples

You can execute any TypeScript example using the repository's `tsn` script:

```bash
npm run tsn -- -T examples/chat-completions/demo.ts
```

Or make the file executable and run it directly:

```bash
chmod +x examples/chat-completions/demo.ts
./examples/chat-completions/demo.ts
```

## Categories Overview

| Directory | Description |
| :--- | :--- |
| [`assistants/`](./assistants) | Creating threads, running assistants, streaming runs, and tool usage |
| [`audio/`](./audio) | Audio transcription (Whisper), translations, and text-to-speech generation |
| [`azure/`](./azure) | Connecting to Azure OpenAI Service for chat, responses, and realtime |
| [`bedrock/`](./bedrock) | Using the AWS Bedrock runtime with SigV4 request signing |
| [`chat-completions/`](./chat-completions) | Streaming completions, function calling, tool use, and structured outputs |
| [`client/`](./client) | Raw response access, custom HTTP headers, error handling, and retries |
| [`fine-tuning/`](./fine-tuning) | Uploading dataset files, creating fine-tuning jobs, and event monitoring |
| [`images/`](./images) | Image generation (`dall-e-3`), editing existing images, and stream handling |
| [`mtls/`](./mtls) | Mutual TLS (mTLS) certificate client configuration |
| [`realtime/`](./realtime) | Low-latency voice and text streaming over WebSockets |
| [`responses/`](./responses) | New Responses API, multi-agent coordination, and background streaming |
