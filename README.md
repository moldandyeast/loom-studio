# Loom Studio (Sep 2026)

**Live:** https://loom-studio-sep-2026.moldandyeast.com

Loom is a small YAML language for humanoid factory work. The compiler turns a
process into a timeline of walks, picks, machine cycles and handoffs, and the
figures play it live with springs, two-bone IK and look-ahead footsteps, with no
keyframes. The whole studio is one self-contained HTML page in `public/`.

## Lineage

1. **Tinker Doom** — https://tinker-doom.moldandyeast.com
2. **Tinker Studio** — https://demo-possie-procedural-bot.moldandyeast.com
   (source: https://github.com/moldandyeast/possies-2)
3. **Loom Studio** — this repo

## Made by RM

More work at **https://content.moldandyeast.com**.

## Deploy

Cloudflare Worker with static assets, custom domain declared in `wrangler.jsonc`.

```sh
npm install
npm run deploy   # wrangler deploy
```
