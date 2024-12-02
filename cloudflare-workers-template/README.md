[![Deploy with Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/zhelezkov/solana-action-templates/tree/main/cloudflare-workers-template)

## Setup

To create a new project using this template, run:

```sh
npm create cloudflare@latest -- --template https://github.com/zhelezkov/solana-action-templates/cloudflare-workers-template
```

## Dev

To test your project, run:

```sh
npm run dev
```

And then open Dialect interstitial website: https://dial.to/?action=solana-action:http://localhost:8787. It'll use your local web server, so you can develop and test almost in realtime.

## Deploy

You can use cloudflare workers to deploy, it's free and has a generous free tier:

```sh
npm run deploy
```

Read more: https://developers.cloudflare.com/workers/

## Useful links

- [Dialect docs](https://docs.dialect.to/documentation/actions)
- [Solana Actions & Blinks specification](https://solana.com/docs/advanced/actions)
- [Dialect examples](https://github.com/dialectlabs/actions)
- [Solana repository](https://github.com/solana-developers/solana-actions)
- [Dialect Blinks React client SDK](https://github.com/dialectlabs/blinks)
- [Dialect Blinks React Native client SDK](https://github.com/dialectlabs/blinks-react-native)