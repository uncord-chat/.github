# Uncord

**Your community. Your server. Your rules.**

Uncord is an open-source, self-hosted chat platform for running your own community. Text channels, voice channels, a deep role and permission system, moderation tools, member onboarding, and a plugin system. All running on your hardware, configured by you, answerable to nobody else.

Communities shouldn't depend on platforms that can change the rules, revoke access, harvest data, disappear, or *demand facial recognition data*. Uncord puts you back in control.

### What's in the box

- **Real-time messaging** with threads, reactions, pins, file attachments, and full-text search
- **Voice and video channels** powered by WebRTC
- **Three-layer permissions** with server defaults, category overrides, and channel overrides
- **Member onboarding** with rules acceptance, email verification, and account age gates
- **Anti-abuse tools** including IP tracking, device fingerprinting, disposable email blocking, and a ban evasion dashboard
- **Server-side plugins** that hook into the event pipeline for custom moderation, integrations, and slash commands
- **One-command deployment** via Docker Compose (Go server + PostgreSQL + Valkey + Typesense)

### Repositories

| Repository | Description |
|-----------|-------------|
| [uncord-server](https://github.com/uncord-chat/uncord-server) | Go server. REST API, WebSocket gateway, permission engine, plugin system |
| [uncord-client](https://github.com/uncord-chat/uncord-client) | React Native client for Windows, macOS, Linux, iOS, and Android |
| [uncord-protocol](https://github.com/uncord-chat/uncord-protocol) | Shared types, permission bitfield constants, event definitions, and OpenAPI spec |
| [uncord-docs](https://github.com/uncord-chat/uncord-docs) | User and admin documentation |

### Quick start
```bash
git clone https://github.com/uncord-chat/uncord-server.git
cd uncord-server
cp .env.example .env    # edit with your settings
docker compose up
```

### Get involved

Uncord is built in the open. If you want to contribute, start with the issues labeled `good first issue` in any repository. Read the [contributing guide](https://github.com/uncord-chat/uncord-server/blob/main/CONTRIBUTING.md) for setup instructions and code conventions.

### License

Server: AGPL-3.0 | Client: MIT | Protocol: MIT

