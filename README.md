# Stone Evenson

Custom software and AI workflows that run in production — tested, documented and yours.
AI agents only where they earn their place.

I build the software and workflows a business runs on, and I build them like software:

- **Simplest thing that works.** Plain code or a deterministic automation first; an AI step where it does the
  work; an agent only when rules can't do the job.
- **Fail closed.** AI can read freely; anything that sends, charges or deletes waits for a human.
- **Idempotent.** A retried webhook never creates a second record or message.
- **Mutation-proven.** Real defects are planted on purpose; the acceptance suite has to go red for every one.
- **Owned by you.** Your accounts, your keys, your code.

## Run a sample

> **Illustrative synthetic scenarios.** Not real clients, results, or testimonials.

- **[d2-missed-call-proof](https://github.com/stoneevenson-biz/d2-missed-call-proof)** — missed call → text-back →
  mock CRM. 30 acceptance tests and 14 planted bugs they must catch.
- **[d1-guardrailed-crm-operator](https://github.com/stoneevenson-biz/d1-guardrailed-crm-operator)** — an AI agent
  works a mock CRM behind a deterministic policy gateway: reads free, writes need a human's scoped approval, sends
  never. 54 acceptance tests and 28 planted bugs caught, including a prompt-injection attack.

Both run on Python's standard library only: no install, no network, no credentials.

## Work with me

Founder of Evenson Systems. Build sprints, or engineering hours on your backlog by the 20-hour block, with a
weekly log of what shipped and what was tested. I build everything myself, so I run one build at a time.

📫 [stone@evensonsystems.com](mailto:stone@evensonsystems.com)

Tools I've built with: Python, JavaScript/TypeScript, Cloudflare Workers, SQLite, GoHighLevel, webhooks and APIs.
