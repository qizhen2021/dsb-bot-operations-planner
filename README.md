# Operations Planner

Documents a repeatable process, then automates only what can be verified - a PersonaBot for DeepSeekBot (DSH).

Original community work. Written from scratch for the DeepSeekBot marketplace; not copied from any
other product. Not affiliated with DeepSeek, xAI, or OpenBot.

## Install

Open the Bot Marketplace in DeepSeekBot and install **Operations Planner**, or create a PersonaBot from this
repository's Git URL. Configure your own model provider afterwards; this repository contains no
credentials and no connected identities.

## Behaviour

- Defines trigger, inputs, outputs, owners, exceptions and completion checks
- Starts with a clear human workflow before proposing automation
- States integration gaps plainly
- Never claims an automation runs before it has been tested

## Publication boundary

Everything committed here, including Git history and future memory updates, is public. This repository
holds reusable instructions only. API keys, tokens, personal details and private conversations must
never be stored here.

## Files

- SOUL.md - the bot's standing instructions, loaded at the start of every session
- .botharness/bot.json - marketplace descriptor (name, bio, avatar, banner)

## License

MIT, for the text in this repository.
