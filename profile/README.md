<p align="center">
  <img src="https://sparringhq.com/icons/icon-512.png" width="96" alt="Sparring" />
</p>

<h1 align="center">Sparring</h1>
<p align="center"><b>Conversation assurance — for AI agents and the people behind them.</b><br/>
Carnegie Intelligent Technology Limited · Hong Kong · <a href="https://sparringhq.com">sparringhq.com</a></p>

---

Point your AI application at the **Sparring Gateway** with one URL change. Every model request is guard‑railed inline, every response is logged (metadata only), sampled conversations are scored by an evidence‑based judge that must quote the transcript, and critical incidents become regression tests automatically. Model tokens pass through at the provider's list price — zero markup. The same judge trains the people who handle the conversations your AI can't.

```ts
// Before                                   // After — one line
new Anthropic({ apiKey: ANTHROPIC_KEY })    new Anthropic({ baseURL: "https://app.sparringhq.com/api/v1/models/anthropic", apiKey: SPARRING_KEY })
```

| | |
|---|---|
| **Product** | [How the gateway works](https://sparringhq.com/product/gateway/) · [Arena (red‑team & CI gate)](https://sparringhq.com/product/arena/) · [Practice](https://sparringhq.com/product/practice/) |
| **Open source** | [`cloud-marketplace-saas`](https://github.com/sparring-hq/cloud-marketplace-saas) — Google Cloud Marketplace + AWS Marketplace integration helpers for SaaS sellers (what we learned shipping two listings) · [`examples`](https://github.com/sparring-hq/examples) — runnable gateway examples |
| **Developers** | [Documentation](https://sparringhq.com/docs/) · [OpenAPI 3.1](https://app.sparringhq.com/api/v1/openapi.json) · [`/v1/health`](https://app.sparringhq.com/api/v1/health) · [Examples →](https://github.com/sparring-hq/examples) |
| **Also by us** | [Carnegie Relay](https://carnegieintel.com/relay/) — AI gateway & governance (budgets, guardrails, traces) on Google Cloud Marketplace and AWS Marketplace |
| **Buy** | [Pricing](https://sparringhq.com/pricing/) · Google Cloud Marketplace (listing in review) |
| **Trust** | [Security](https://sparringhq.com/security/) · [Status](https://status.sparringhq.com) · [DPA](https://sparringhq.com/legal/dpa/) · [AUP](https://sparringhq.com/legal/aup/) · [Sub‑processors](https://sparringhq.com/legal/subprocessors/) |
| **Standard** | [Sparring Conversation Standard v1.0](https://sparringhq.com/standard/) — 5 competencies, 34 skills, evidence rule |
| **Contact** | support@sparringhq.com · security@sparringhq.com (disclosures) · hello@sparringhq.com |

<sub>Sparring is built and operated by Carnegie Intelligent Technology Limited (Company No. 80704751, Hong Kong). The product itself is proprietary; this organization hosts public examples, SDK helpers and integration templates.</sub>
