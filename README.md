<p align="center">
  <img src="./assets/profile-banner.svg" alt="Uzair Ansari — frontend engineer and full-stack builder" width="100%" />
</p>

<p align="center">
  <a href="https://uzairansari11.vercel.app/">🌐 Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/uzairansari11/">💼 LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:uzairans532@gmail.com">✉️ Say hello</a>
</p>

## I make complex products feel simple.

Hi, I'm **Uzair** — a frontend-focused software engineer in Mumbai with around **3 years of experience**. I build interfaces people enjoy using and dig into the systems behind them when the product needs it. My work spans enterprise workflows, real-time communication, and AI-powered experiences.

| **4** | **1,500+** | **3** |
| :---: | :---: | :---: |
| Production applications built from scratch | Users on a calling platform | Junior developers mentored |

**Explore:** [Professional projects](#professional-projects) · [What I'm building now](#what-im-building-now) · [Public code](#public-code) · [Toolkit](#toolkit)

## Professional projects

*TalkWisely Platforms · Software Engineer · 2024–2026*

### 💸 AI-powered finance platform — less time on repetitive analysis

I built the frontend for financial analysis, OCR-based invoice processing, and forecasting workflows. The result was **70% less analyst effort** and **80% faster invoice verification**.

The UI later needed more flexibility and better behavior across browsers. I migrated it from **HeroUI to shadcn/ui**, module by module, while preserving the existing state, business logic, and API integrations.

### 🧩 Custom ERP-style CRM — faster, more reliable workflows

I architected the frontend for a **10+ module** CRM with role-based dashboards and workflows. It covered quotations, inventory, and procurement. Automating the quotation flow reduced **quote creation time by 97%** and **errors by 90%**.

The work involved translating complicated business rules into forms and interfaces that teams could use day to day.

### 📞 VoIP calling platform — real-time work at scale

I built a low-latency browser calling experience with **React and SIP.js** for **1,500+ users**. Real-time dashboards and call management features reduced call handling time by **35%**.

One tricky issue was overlapping audio across multiple call sessions. I moved audio handling to individual sessions and cleaned up resources when calls ended, making the experience more dependable.

<details>
<summary>What this taught me</summary>

A call isn't finished just because its UI disappears. Real-time interfaces need explicit ownership and cleanup for every active session, media element, and event listener.

</details>

### 📋 Internal project management — replacing a paid tool

I drove frontend development for a project management and time-tracking application covering tasks, hours, and performance. It replaced a paid SaaS solution. A shared component library made future feature delivery **40% faster**.

**Earlier work:** At **Fastor7 Technology**, I built 5+ Next.js dashboard modules for orders, inventory, and seller analytics across 5+ internal teams, improving performance by 25%. At **Clayfin Technologies**, I built booking and leave-management workflows with multi-level approvals for 100+ employees.

## What I'm building now

### 🔎 DocuMind — answers that point to the source

I'm building a document assistant that answers questions about uploaded PDFs with **source citations**. The interesting part is everything between a question and an answer: query rewriting, semantic retrieval, reranking, context selection, and streaming the result to the interface. I also built a background pipeline that turns PDFs into AI-generated podcasts.

`Upload → extract → embed → retrieve → rerank → cite and stream`

**Built with:** React, Node.js, Express, PostgreSQL, Prisma, Qdrant, Redis, BullMQ, AWS S3, and OpenAI APIs.

## Public code

Some of my product work is private, but these repositories show parts of how I build:

### 👕 Clothify — storefront, API, and admin dashboard

I built a full-stack shopping application with product discovery, cart, wishlist, checkout, and order management. The admin area handles products and orders with role-based access. It's a good place to see my **React and Redux frontend** alongside an **Express and MongoDB API**. [Explore the code →](https://github.com/uzairansari11/Clothify)

<p align="center">
  <a href="https://github.com/uzairansari11/Clothify">
    <img src="https://raw.githubusercontent.com/uzairansari11/Clothify/main/Frontend/clothify/screenshots/14-admin-dashboard.png" alt="Clothify admin dashboard showing store metrics and management navigation" width="750" />
  </a>
</p>

**More projects:**

| Start here | What you'll find | Stack |
| --- | --- | --- |
| [💬 ChatApp](https://github.com/uzairansari11/ChatApp) | A real-time chat frontend and API | React, Socket.IO, Express, MongoDB |
| [🛍️ Product catalog](https://github.com/uzairansari11/simfoni_assignment) | Search, filtering, sorting, and responsive product pages | React, TypeScript, Redux, Tailwind CSS |
| [📄 Resume Builder](https://github.com/uzairansari11/resume_builder) | Form-driven resume creation and PDF export | React, Bootstrap |

## Toolkit

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind,nodejs,express,postgres,prisma,redis" alt="React, Next.js, TypeScript, Tailwind CSS, Node.js, Express, PostgreSQL, Prisma, Redis" />
</p>

| I reach for | When I'm building |
| --- | --- |
| **React · Next.js · TypeScript · Tailwind CSS · shadcn/ui** | Clear, responsive interfaces |
| **Redux Toolkit · TanStack Query · SSE** | State, server data, and streamed experiences |
| **Node.js · Express · PostgreSQL · Prisma · Redis** | APIs, persistence, and background work |
| **LangChain · Qdrant · OpenAI APIs** | Retrieval and AI-powered features |

**Currently learning:** FastAPI and SQLAlchemy, while going deeper on AI agents and the architecture behind reliable AI applications.

## Let's connect

If you're building something with a tricky interface, real-time behavior, or a useful AI feature, I'd love to hear about it. [Email me](mailto:uzairans532@gmail.com) or [connect on LinkedIn](https://www.linkedin.com/in/uzairansari11/).
