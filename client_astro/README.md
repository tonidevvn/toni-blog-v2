# Toni portfolio — Astro

An Astro copy of `client_nextjs`. Astro owns the page document and static build; the existing portfolio runs as one client-only React island so its theme, navigation, animations, and 3D model behave the same way.

## Requirements

- Node.js 22.12 or newer
- pnpm

## Run locally

```bash
pnpm install
pnpm dev
```

Open the local URL printed by Astro (normally `http://localhost:4321`).

## Validate and build

```bash
pnpm check
pnpm build
pnpm preview
```

The production output is in `dist/` and can be deployed as a static site.
