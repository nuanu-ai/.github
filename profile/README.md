# Nuanu AI

## Immunity Core

The open-source detection core of Artificial Immunity, for one Mac where AI coding agents work. It checks dependencies against OSV and CISA data, judges program starts and new files with SigmaHQ and Elastic rules, says how bad and how sure each finding is, and says what it could not see. It reports and blocks nothing. Apple Silicon, macOS 15 or later, Rust, MIT.

- Code: [nuanu-ai/immunity-core](https://github.com/nuanu-ai/immunity-core)
- Website: [immunity.bot](https://immunity.bot)
- Docs: [immunity.bot/docs](https://immunity.bot/docs/)
- Build: `git clone https://github.com/nuanu-ai/immunity-core && cd immunity-core && ./build`

## Agent Payment Node (APN)

Open-source, local-first payment runtime and MCP server for AI agents: x402 purchases, USDC and token transfers on EVM,
Solana and TRON, bridges and swaps under limits the owner sets. Direct transfers wait for the owner's approval in a terminal.

- Code: [nuanu-ai/agent-payment-node](https://github.com/nuanu-ai/agent-payment-node)
- Website: [agentpaymentnode.com](https://agentpaymentnode.com)
- Install: `brew install nuanu-ai/tap/apn`
