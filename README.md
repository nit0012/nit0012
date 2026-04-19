

# Nitish Ojha

**Backend Engineer · Full-Stack Developer · CSE '27**

[![Portfolio](https://img.shields.io/badge/Portfolio-nitishojha.in-111110?style=flat-square&logo=vercel&logoColor=white)](https://www.nitishojha.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nitishojha00-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/nitishojha00/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Top_8%25-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/__Nitish___Ojha/)
[![Codeforces](https://img.shields.io/badge/Codeforces-Global_395-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/nitishojha00)
[![X](https://img.shields.io/badge/X-nitishojha00-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/nitishojha00/)




---

I build production-grade backend systems — caching layers, job queues, real-time APIs, and auth pipelines.  
Currently a 3rd-year CSE student; open to **SDE internships** and **backend collaborations**.

---

## Projects

### [CODTRAKR](https://github.com/Nitishojha00/COD_TRAKR) — Competitive Programming Tracker
> Node.js · Express · Redis · BullMQ · MongoDB · Puppeteer · AWS SES

- **Multi-layer caching**: platform Redis (15min TTL) + user dashboard (24h TTL) + client localStorage → **60–80% cache hit rate**, zero API calls on repeat visits
- **Background job queue** with BullMQ (concurrency=5) + Redis-locked workers — server never blocks on slow Puppeteer scrapers
- Custom scrapers for **4 platforms**: GraphQL/REST for LeetCode + Codeforces; headless Puppeteer for CodeChef + GFG
- Rate limiting built **from scratch** using Redis `INCR+EXPIRE` — no external library; stateless JWT auth with HTTP-only cookies + OTP via AWS SES

### [Talksy](https://github.com/Nitishojha00/Talksy) — Real-Time Chat App
> Node.js · Socket.IO · MongoDB · JWT · React · Vite

- Fault-tolerant WebSocket with auto long-polling fallback + ping-pong heartbeat → **99.9% connection uptime** across unstable networks
- Stateless horizontal JWT auth (48h, bcrypt, strict CORS) securing REST APIs and Socket.IO simultaneously
- 1-on-1 + group chat with typing indicators, online status, CRUD — optimized via **MongoDB aggregation pipelines**

---

## Tech Stack

```
Backend     Node.js  ·  Express.js  ·  REST API  ·  WebSocket  ·  BullMQ  ·  JWT
Databases   MongoDB  ·  Redis  ·  PostgreSQL  ·  MySQL
Frontend    React.js  ·  Redux  ·  Tailwind CSS
Cloud       AWS SES  ·  Docker  ·  GitHub Actions  ·  Vercel  ·  Cloudflare
Languages   JavaScript  ·  TypeScript  ·  C/C++  ·  Python  ·  SQL
Tools       Puppeteer  ·  Postman  ·  Linux CLI  ·  Bash  ·  Git
Core CS     DSA  ·  OOP  ·  OS  ·  DBMS  ·  CN
```

---

## Competitive Programming

| Platform | Rating / Rank | Problems |
|---|---|---|
| LeetCode | **1800+** (Top 8%) | 350+ |
| Codeforces | **Global Rank 395** (Midnight Code Cup 2026) | — |
| CodeChef | **1500+** | — |
| Combined | — | **1000+** solved |

---

## GitHub Stats














---




**nitishojha00@gmail.com · +91-7355921679 · Kanpur, UP**



