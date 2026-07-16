<h1 align="center">Tyler Henson</h1>

<p align="center">
  <b>Founder &amp; CEO @ TourneyTek, Inc.</b> · Building <a href="https://www.pokerhawk.io">Poker Hawk</a>
</p>

<p align="center">
  I run the company and write the code.
</p>

<p align="center">
  <a href="https://www.pokerhawk.io"><img alt="Poker Hawk" src="https://img.shields.io/badge/Poker_Hawk-pokerhawk.io-1f6f4a?style=for-the-badge&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/tyler-henson-354abb1ba"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:tyler.henson@tourneytek.com"><img alt="Email" src="https://img.shields.io/badge/Email-tyler.henson%40tourneytek.com-c14438?style=for-the-badge&logo=maildotru&logoColor=white"></a>
</p>

---

### What I'm building

**[Poker Hawk](https://www.pokerhawk.io)** — a tournament platform for poker clubs and home games. One synchronized clock across every screen in the room, with blind structures, check-in, table balancing, payouts, and leaderboards built in. Free forever for players.

It runs everywhere the room does:

| Surface | What it is | Built with |
| --- | --- | --- |
| **Desktop** | The host command center — live control of clock, structure, tables, payouts | Electron + React |
| **Mobile** | Free player app plus on-the-go director controls | React Native (Expo), iOS &amp; Android |
| **Web** | Marketing site, accounts, billing, and Hawk Academy | Next.js on Vercel |
| **TV** | Public blind and level displays over the table | Android — Fire TV &amp; Google TV |
| **Admin** | Internal ops, support, and moderation portals | Next.js + React Native |

All of it lives in one TypeScript monorepo (pnpm + Turborepo) on a Firebase backend — Firestore, Realtime Database, Cloud Functions, and Auth — with Stripe and RevenueCat handling billing and Sentry watching every surface.

### Open source

Pieces of that platform that stand on their own, pulled out and published. Zero dependencies, fully typed, MIT.

| | |
| --- | --- |
| **[tournament-math](https://github.com/TourneyTek-Inc/tournament-math)** | ICM equity (Malmuth-Harville), payout curves, table balancing, close-table seat planning, and stack pressure — the math behind running a live tournament. |
| **[sentry-scrub](https://github.com/TourneyTek-Inc/sentry-scrub)** | Strip PII and secrets out of Sentry events before they leave the process. Single-pass, never-throws, no SDK dependency. |
| **[blind-structure](https://github.com/TourneyTek-Inc/blind-structure)** | Blind schedules generated from player count, stack and target duration — aware of which chips are actually on the table. |

### How I work

Founder and engineer are the same job here, so one day covers payout math and pricing, positioning and push notifications. What I optimize for:

- **Shipping to real rooms.** Poker Hawk runs live tournaments, where a dropped clock is somebody's night. Reliability isn't a feature, it's the product.
- **One codebase, many screens.** Shared domain logic in a core package, thin platform surfaces on top. Sync is the hard part, so it gets the attention.
- **Boring infrastructure.** Typed end to end, tested where it counts, and documented in the same PR as the change.

### Tools of the trade

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

> Most of my work lives in private product repos, so the graph below is the honest record of the shipping.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/recondemon/recondemon/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/recondemon/recondemon/output/snake-light.svg">
  <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/recondemon/recondemon/output/snake-light.svg">
</picture>

---

<p align="center">
  <sub>Running a poker night that deserves better than a spreadsheet and a stopwatch? <a href="https://www.pokerhawk.io">Start here.</a></sub>
</p>