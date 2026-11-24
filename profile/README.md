# Plugsky

**39 models. One OpenAI-compatible API. Flat monthly plans.**

Plugsky is an OpenAI-compatible AI API with 39 public model IDs. Builder and Scale have no monthly token cap, no per-token overage and no pay-as-you-go meter; fair-use concurrency, RPM and context limits still apply. Free tier: $0, no card.

- Website: https://plugsky.com
- Docs: https://plugsky.com/docs
- Pricing: https://plugsky.com/pricing
- Flat-rate definition: https://plugsky.com/flat-rate-ai-api
- Free API key: https://plugsky.com/free-api-key
- MCP endpoint: https://plugsky.com/mcp
- Agent configs: https://github.com/coinplannet/plugsky-agent-configs

## Quick start

```bash
curl https://api.plugsky.com/v1/chat/completions \
  -H "Authorization: Bearer $PLUGSKY_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "plugsky-micro",
    "messages": [{"role": "user", "content": "Hello"}]
  }'
```

## What is in this organization

- `plugskyCLI` — command-line client
- `plugsky-mcp` — MCP server and listing metadata
- `plugsky-agent-configs` — OpenClaw, Hermes, OpenCode, Codex, Cline and Open WebUI recipes

## Links

- X: https://x.com/plugskycom
- LinkedIn: https://www.linkedin.com/company/plugsky
- YouTube: https://www.youtube.com/channel/UCt4Vj4xMI4K4ecdD7Fpcubg
- Medium: https://medium.com/plugsky
- DEV: https://dev.to/plugsky-ai
