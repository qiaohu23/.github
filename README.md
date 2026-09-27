# HeyRepli

**AI social media concierge for SMB.** Scrape 6 platforms, AI rewrite content, publish to Twitter/LinkedIn/Facebook — all through one API.

## What we build

- 🔌 **[heyrepli-js](https://github.com/qiaohu23/heyrepli-js)** — TypeScript SDK covering all 13 MCP tools
- 📚 **[heyrepli-examples](https://github.com/qiaohu23/heyrepli-examples)** — n8n, Make, Python, OpenClaw integration examples
- 🤖 **HeyRepli API** — 6 scraping tools + 10 publish targets + AI rewrite
- 🎯 **HeyRepli App** — social media concierge for SMB owners

## Quick install

```bash
npm install heyrepli
```

```typescript
import { HeyRepli } from "heyrepli";
const hr = new HeyRepli({ apiKey: process.env.HEYREPLI_API_KEY! });
const t = await hr.youtube.transcript("dQw4w9WgXcQ");
console.log(t.fullText.slice(0, 100));
```

## 11 platforms supported

| Scrape | Publish |
|---|---|
| YouTube (transcript + metadata + search) | Twitter, LinkedIn, Facebook |
| TikTok | Pinterest, Bluesky, Mastodon |
| Instagram | Instagram, TikTok, YouTube |
| Twitter/X | Threads |
| LinkedIn | |
| Facebook | |
| Threads, Bluesky, Mastodon (REST) | |
| Reddit (mention listening) | |

## Get an API key

Free tier: 50 AI replies + 5 rewrites + 10 scheduled posts/month.

[https://app.heyrepli.com/dashboard/settings/account](https://app.heyrepli.com/dashboard/settings/account)

## Links

- Website: [https://heyrepli.com](https://heyrepli.com)
- Docs: [https://heyrepli.com/pricing](https://heyrepli.com/pricing)
- Blog: [https://heyrepli.com/blog](https://heyrepli.com/blog)
- Twitter: [@heyrepli](https://twitter.com/heyrepli)
