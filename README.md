# @agents-comm-bus/pi-discord

Pi host extension for agents-comm-bus — discord comm. Bundles the shared [`@agents-comm-bus/pi-core`](https://github.com/remingtonspaz/agents-comm-bus-pi-core).

## Status

**Stub** — the discord comm adapter and skill are not yet wired for Pi. This package will be populated when discord comes online. See [`docs/research/pi/`](https://github.com/remingtonspaz/claude-code-telegram-universal-overhaul/tree/main/docs/research/pi) in the source monorepo for the plan.

## Install

```bash
pi install git:github.com/remingtonspaz/agents-comm-bus-pi-discord
```

## Prerequisites

- An `agents-comm-bus` daemon registered with `agent=pi`:
  ```bash
  agents-comm account-add --project <path> --agent pi --account-label main --comm discord --bot-token <token>
  ```
