<p align="center">
  <img alt="orboto" src="https://raw.githubusercontent.com/Orboto/.github/main/source/logo_orboto_dot_white.svg" height="80">
</p>

<p align="center">
  <strong>Enterprise project and ticket management, built for humans and AI agents.</strong><br>
  Self-hostable, EU-hosted, GDPR-friendly - sovereign by design, with agents as permissioned teammates instead of a chatbot bolted on top.
</p>

<p align="center">
  <a href="https://orboto.io">Website</a> ·
  <a href="https://orboto.io/waitlist">Join the Waitlist</a> ·
  <a href="https://x.com/orboto_io">@orboto_io</a>
</p>

---

## What we build

orboto is a full-featured, enterprise-grade ticket and project management platform for
teams that demand **data sovereignty**, **deep AI integration**, and a system that
**autonomous coding agents can talk to natively**. Run it self-hosted on your own
infrastructure in the EU, or let us host it for you - either way your data stays yours,
with a clean one-click path back out and no lock-in.

One platform for everything around getting work done:

- 🎯 **Plan** - Tickets, epics, milestones, versions, dependencies, Gantt timelines, critical-path and capacity planning
- 🚀 **Execute** - Kanban, list, table and Gantt views, real-time collaboration, time tracking, timesheets, RACI
- 📚 **Document** - Nested wiki with Smart Links, revisions, backlinks, PDF export
- 📊 **Measure** - Burndown, velocity, cycle-time, workload, Earned Value Management, customisable dashboards
- 🤖 **Automate** - In-app AI assistant, project primer, OQL/JQL search, alert rules, inbound email, webhooks, MCP server
- 🔒 **Govern** - PBAC, SSO (OIDC + SAML), guest access, audit log, compliance-evidence bundles, federation
- 🔄 **Migrate** - One-click imports from Jira, Linear, GitHub, GitLab, Asana, Trello, Redmine and CSV

## Enterprise and EU sovereignty

Built for organisations that have to answer to security, legal and compliance - not just
to a backlog.

- **Self-hosted or EU-hosted** - bring your own Postgres and object storage, deploy on any Docker host or Kubernetes cluster, keep every byte inside your own infrastructure
- **GDPR-ready** - per-user data export and anonymisation, scoped to a dedicated operator role
- **Single Sign-On** - OpenID Connect and SAML 2.0 with just-in-time provisioning, domain enforcement and multiple parallel identity providers (Entra ID, Okta, Google Workspace, Auth0, Keycloak)
- **Granular access control** - permission-based access control down to the action, global and per-project roles, private tickets, and opt-in guest access for clients and contractors
- **Audit everything** - every admin action, AI call, backup run and settings change recorded with full actor attribution
- **Compliance evidence export** - one-click signed ZIP bundles formatted for BSI-C5 or SOC-2 auditors, with a SHA-256 manifest of every file
- **Multi-instance federation** - mirror ticket and project data between independent workspaces with per-link direction control and HMAC-signed transport
- **Cross-organisation sharing** - share a single project with a partner's instance without exposing your workspace; internal comments, budgets and rates never leave your box
- **Workspace branding** - make orboto look like your product with custom logo, colour and workspace name
- **Bring your own AI key** - run Ollama locally and nothing leaves your infrastructure; or pick OpenAI, Anthropic or Google Gemini per your policy

## Built for the AI-agent era

orboto is one of the few project trackers that treats autonomous coding agents
as **first-class team members**, not as an afterthought. Agents claim a ticket, do the
work, link their commits, move it through review and close it - under the **exact same
permissions and audit trail as a human**, following binding workspace rules you control.

- **Native MCP server** - connect Claude, Cursor, Copilot or any MCP-aware client and operate orboto through structured tools and resources, tickets and the full wiki surface included
- **In-app AI assistant** - ask and act in plain language; every write waits for your approval and lands in the audit log
- **Agent skill file** - drop-in guide so any LLM agent operates as a team member through the REST API, self-syncing with the instance it talks to
- **Structured project memory** - facts, epics, stories and acceptance criteria give agents a real context home, so they build the right thing
- **Governance, not just access** - binding rules (claim, commit, close, one commit per ticket, write in the workspace language) every agent follows, under the same PBAC and audit trail as people

The AI does plumbing, not magic - summaries, duplicate detection, effort estimation,
natural-language search, label and priority suggestions, milestone risk and retrospectives.
Turn it off and you still have a complete, production-grade tracker.

## Why orboto

- **Sovereign by design** - self-hostable, EU-hosted, GDPR-friendly, with full export and a clean migration path out. No lock-in is a feature, not a confession.
- **Agents are teammates, not a feature** - they live inside the permission model, not in a sidebar
- **The whole kit, not an MVP** - time tracking, capacity, analytics, alerts, SSO, federation and its own query language, production-ready on day one
- **Near-zero switching cost** - one-click imports keep your source IDs, users, labels, comments and time
- **Speaks your language** - content in 18 languages, UI shipping in English, German, French, Italian and Spanish with more each release

## Tech we love

`TypeScript` · `Fastify` · `React` · `PostgreSQL` · `Drizzle ORM` ·
`Tailwind` · `shadcn/ui` · `TanStack Query` · `Zod` · `Turborepo`

## Get in touch

- 🌐 Learn more at **[orboto.io](https://orboto.io)**
- 📧 Reach the team at **hello@orboto.io**
- 🐛 Spotted something? Open an issue in the relevant repository

<p align="center">
  <sub>Made with care in Germany 🇩🇪</sub>
</p>
