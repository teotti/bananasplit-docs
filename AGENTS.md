# BananaSplit Documentation

This is the documentation site for BananaSplit, built on [Mintlify](https://mintlify.com).

## About BananaSplit

BananaSplit is an expense tracking app for splitting costs with friends across vacations, roommates, couples, and group events. It provides:

- **CLI** — terminal access to expenses, balances, groups, and payments
- **Agent skill** — AI agents can manage expenses via shell commands
- **QR Code API** — generate QR codes programmatically (no auth required)

## Project structure

```
/                     # Root pages (index, quickstart)
/cli/                 # CLI documentation
/agents/              # Agent integration guides
/qr-code/             # QR Code API reference
docs.json             # Mintlify configuration
llms.txt              # Agent-friendly summary
```

## Terminology

- **expense** — a cost to be split among people
- **payment** — a settlement between two people
- **group** — a collection of people sharing expenses (trips, roommates, etc.)
- **split** — how an expense is divided among participants
- **balance** — what someone owes or is owed

## Style

- Casual, friendly tone ("no awkwardness, just good times")
- Active voice, second person ("you")
- Concise sentences
- Code for commands, file names, and technical references
- Names over IDs in examples

## Brand colors

- Primary: `#7b260f` (warm brown)
- Accent: `#ffe66f` (banana yellow)
- Background: `#fafafa`

## Content scope

Document:
- CLI installation, authentication, and all commands
- Agent skill installation and usage
- QR Code API endpoints and examples

Do not document:
- Internal API endpoints (use CLI instead)
- Mobile app internals
- Admin features

## Mintlify tools

- Use the Mintlify MCP server at `https://mcp.mintlify.com` for content editing
- Use the Mintlify docs MCP server at `https://www.mintlify.com/docs/mcp` for Mintlify features
- Install the Mintlify skill: `npx skills add https://mintlify.com/docs`
