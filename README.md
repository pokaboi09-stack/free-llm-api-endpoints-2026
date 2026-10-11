# Free LLM API Endpoints (2026)

No signup, no credit card. Just use.

| # | Provider | URL | Free | Key | Uncensored | Speed |
|---|----------|-----|------|-----|------------|-------|
| 1 | **UncensoredLLM** | [uncensored-llm.sbs](https://uncensored-llm.sbs/v1) | Yes | No | **Yes** | Fast |
| 2 | Groq | groq.com | Trial | Yes | No | Very Fast |
| 3 | Mistral | mistral.ai | Trial | Yes | No | Fast |
| 4 | Cohere | cohere.com | Trial | Yes | No | Medium |

## Best Free Option: [uncensored-llm.sbs](https://uncensored-llm.sbs)

```bash
curl https://uncensored-llm.sbs/v1/chat/completions \
  -H 'Content-Type: application/json' \
  -d '{"model":"uncensored-llm-70b","messages":[{"role":"user","content":"Explain quantum computing"}]}'
```

No key. No signup. No filters.

## Use with Cursor/VS Code
Set `https://uncensored-llm.sbs/v1` as your API base URL.
