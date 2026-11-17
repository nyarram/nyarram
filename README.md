### Hi, I'm Nikhil 👋

Backend engineer at **Chewy** on the orders platform, building order management features in **Java / Spring Boot** on AWS and keeping them healthy in production. Outside work I build tooling for AI agents: evaluation, security, and production LLM pipelines.

📍 Minneapolis, relocating to the Bay Area · 🌐 [yarramnikhil.com](https://yarramnikhil.com) · 💼 [LinkedIn](https://www.linkedin.com/in/nikhil-yarram-845bb7167/)

---

#### What I've built

**[identity-broker](https://github.com/nyarram/identity-broker)** · Java, Spring Boot, Cedar, Postgres<br>
Gives AI agents short-lived, single-action credentials (OAuth token exchange, RFC 8693/9396). In the demo, a prompt-injected agent tries to refund every order. The broker denies each out-of-task action and records it in a hash-chained audit log.

**[litmus](https://github.com/nyarram/litmus)** · Python, OpenTelemetry<br>
Open-source eval harness for LLM pipelines: versioned golden datasets, calibrated LLM judges, and CI gates that fail the build when quality regresses. Every score traces back to the model call behind it.

**[astrodigest](https://github.com/nyarram/astrodigest)** · TypeScript, Next.js, React Native, BullMQ · [live demo](https://astrodigest-web.vercel.app)<br>
A weekly AI-curated astronomy digest for web and mobile. Content from NASA, ESO, and arXiv is ingested daily, then scored, summarized, and editorially checked by a worker pipeline. Litmus evaluates its scoring.

**[lims](https://github.com/nyarram/lims)** · Python, Django, PostgreSQL<br>
Sample-tracking and inventory backend for a regulated lab. Invariants and a tamper-evident audit trail are enforced in the database, so no writer can bypass them. Tested with 64 tests against real Postgres.

---

#### Stack

**Work:** Java · Spring Boot · AWS (SQS, SNS) · Kafka · PostgreSQL · Docker · Kubernetes<br>
**Side projects:** Python · TypeScript · Node / Fastify · Next.js · React Native · Redis · OpenTelemetry
