To add **Varlock** to the repository, I have introduced a new **Security & Secrets** category, as Varlock represents a specialized "secrets infrastructure" layer designed specifically for the unique failure modes of AI agents (such as leaking credentials into context windows or logs).

Here is the updated `README.md` content:

```markdown
# Awesome Agent Infrastructure

> "Make something agents want" replaces "make something people want" — agents will autonomously choose the best tools, bypassing ads and sales entirely.
— [Aaron Levie](https://x.com/levie/status/2030714592238956960)
> 

A curated list of infrastructure, tools, and services designed for the agentic era, where software is built for autonomous AI agents to use, navigate, and transact.

---

## 🏗️ Compute & Runtime

*Sandboxed environments for agents to execute code safely.*

- [**E2B**](https://e2b.dev/) – Cloud runtime for AI agents and apps. Secure sandboxes for code execution.
- [**Modal**](https://modal.com/) – High-performance serverless compute for AI models and data-intensive tasks.
- [**Cloudflare**](https://www.cloudflare.com/) – Global edge network for low-latency agent logic and sandboxed workers.

## 📁 File Systems & Memory

*Storage and hosting specialized for agent artifacts and persistent state.*

- [**Box**](https://www.box.com/) – Enterprise-grade file system and content cloud for agent memory and document management.
- [**here.now**](https://here.now/) – Instant web hosting for agent-generated artifacts (dashboards, tools, prototypes).

## 🔒 Security & Secrets

*Infrastructure for protecting agent credentials and preventing sensitive data leaks.*

- [**Varlock**](https://varlock.dev/) – Secure-by-default environment variable management designed to keep secrets out of agent context, logs, and terminal output.

## 🔍 Agent-Optimized Search

*Search engines built for LLM retrieval and autonomous discovery.*

- [**Exa**](https://exa.ai/) – A search engine designed specifically for AI agents, prioritizing clean data over SEO.

## 💳 Agent Wallets & Payments

*Financial infrastructure enabling agents to pay and be paid autonomously.*

- [**Stripe**](https://stripe.com/) – Global payment infrastructure for agentic commerce and billing.
- [**Coinbase**](https://www.coinbase.com/) – Crypto-native wallets and on-chain payment rails for autonomous agents.

## 📬 Communication

*Protocols and services for agent-to-human and agent-to-agent messaging.*

- [**Agentmail**](https://agentmail.com/) – Specialized email infrastructure designed for AI agent communication.

---

### Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

```
