<!--

          N
         ╱│╲
        ╱ │ ╲
       ╱  │  ╲             Reading source at 2am?
      W───●───E            Good. That is how I find people worth working with.
       ╲  │  ╱
        ╲ │ ╱              Transmit → contact@moradz.dev
         ╲│╱
          S

-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:070605,45:0d0a07,80:241505,100:7a4708&height=220&section=header&text=Morad%20Zubedat.&fontSize=64&fontColor=f4f0e8&animation=fadeIn&fontAlignY=38&desc=Navigation%20%C2%B7%20Localization%20%C2%B7%20Systems%20%C2%B7%20Cyber&descSize=20&descAlignY=58" width="100%" alt="header banner"/>

<a href="https://github.com/morad-z">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=F5A21B&center=true&vCenter=true&width=760&lines=Software+Engineer+%E2%80%94+Cyber+%C2%B7+Full-stack+%C2%B7+Backend;C%2B%2B+visual-inertial+odometry+that+holds+when+GPS+drops;Desktop+systems+that+real+businesses+run+on;Offensive+%26+defensive+security+%E2%80%94+Layer-2%2C+RCE+chains;TDD+%C2%B7+Clean+Architecture+%C2%B7+Dead+reckoning" alt="typing animation"/>
</a>

<br/><br/>

`───` B.Sc. Software Engineering — Shenkar, 2026 · Haifa, IL `───`

<table>
<tr>
<td align="center"><code>[ ROLE ]</code><br/><br/><b>Software Engineer</b></td>
<td align="center"><code>[ FOCUS ]</code><br/><br/><b>Cyber · Full-stack · Backend</b></td>
<td align="center"><code>[ BASED ]</code><br/><br/><b>Haifa, Israel</b></td>
<td align="center"><code>[ STATUS ]</code><br/><br/><b>Open to junior & new-grad roles</b></td>
</tr>
</table>

<a href="https://www.moradz.dev">
  <img src="https://img.shields.io/badge/Portfolio-moradz.dev-f5a21b?style=for-the-badge&labelColor=070605&logo=googlechrome&logoColor=f4f0e8" alt="Portfolio"/>
</a>
<a href="https://www.linkedin.com/in/morad-zubedat/">
  <img src="https://img.shields.io/badge/LinkedIn-in%2Fmorad--zubedat-e0930f?style=for-the-badge&labelColor=070605&logo=linkedin&logoColor=f4f0e8" alt="LinkedIn"/>
</a>
<a href="mailto:contact@moradz.dev">
  <img src="https://img.shields.io/badge/Email-contact@moradz.dev-cf7d08?style=for-the-badge&labelColor=070605&logo=gmail&logoColor=f4f0e8" alt="Email"/>
</a>
<a href="https://github.com/morad-z">
  <img src="https://img.shields.io/badge/GitHub-morad--z-b8690a?style=for-the-badge&labelColor=070605&logo=github&logoColor=f4f0e8" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=morad-z&color=f5a21b&style=flat-square&label=PROFILE+VIEWS" alt="profile views"/>
<a href="https://github.com/morad-z?tab=followers">
  <img src="https://img.shields.io/github/followers/morad-z?style=flat-square&logo=github&color=cf7d08&labelColor=070605&label=FOLLOWERS" alt="followers"/>
</a>
<a href="https://github.com/morad-z?tab=repositories">
  <img src="https://img.shields.io/github/stars/morad-z?style=flat-square&logo=github&color=f5a21b&labelColor=070605&label=STARS&affiliations=OWNER" alt="stars"/>
</a>

</div>

---

###### `01 / ABOUT`

## Navigation engines, payroll systems, attack labs.

Software Engineering graduate from Shenkar (B.Sc., 2026). My final project, **NavSight** — a C++ visual-inertial odometry engine that navigates an Android phone when GPS is gone — was graded 100/100 and held 91–93% distance accuracy through real GNSS jamming. Around it: **XPlanner**, a shift-and-payroll system accountants use in the field; **B.H Nur**, ops software for a family construction business; and **Skambil**, a multiplayer card game with an authoritative server.

Most of my work sits between the web and low-level systems — Android + C++ over JNI, AWS serverless pipelines, network attack-and-defense labs in Scapy. The software I care about is the kind you measure in months of uptime, not demos.

<div align="center">

<table>
<tr>
<td align="center"><code>[ DEGREE ]</code><br/><br/><b>B.Sc. · 2026</b></td>
<td align="center"><code>[ REPOS ]</code><br/><br/><b>40+</b></td>
<td align="center"><code>[ LANGUAGES ]</code><br/><br/><b>AR · HE · EN</b></td>
</tr>
<tr>
<td align="center"><code>[ IN PRODUCTION ]</code><br/><br/><b>3 systems</b></td>
<td align="center"><code>[ FINAL PROJECT ]</code><br/><br/><b>100 / 100</b></td>
<td align="center"><code>[ AWARD ]</code><br/><br/><b>1st — UX Challenge</b></td>
</tr>
</table>

</div>

> `[ AVAILABILITY ]` B.Sc. 2026 · Open to junior and new-grad roles — cyber, full-stack, backend

---

###### `02 / SELECTED WORK`

## Selected work

`13 projects · 2024 — 2026`

<details>
<summary><code>01</code> <b>NavSight</b> — GPS-denied navigation for Android · <code>Complete · B.Sc. final project · 100/100</code></summary>
<br/>

**Android navigation that keeps tracking position when GPS drops — using only the camera and the phone's inertial sensors.** A C++ visual-inertial core (15-DOF error-state EKF, KLT optical flow, IMU preintegration) reads metric speed off the road plane and an on-device Viterbi HMM map matcher pins the position to an OpenStreetMap road graph held in local storage. Built and measured in Haifa during wide-area GNSS jamming that froze the phone's own GPS for 61 s and inflated a 1,280 m route by 33%.

| Attribute | Details |
|:----------|:--------|
| **Stack** | C++ · Kotlin · Jetpack Compose · OpenCV · Android NDK · JNI · CMake · OpenStreetMap |
| **Results** | **91–93% travelled-distance accuracy** under active jamming; median speed within 3.5% of reference; exactly 0 km/h at standstill |
| **Performance** | **15.4 ms/frame** median tracking cost — 13x under the 200 ms budget; 13/13 system tests passing |
| **Security** | Fully on-device — no GPS dependency, no network round-trip, no location data leaves the phone |
| **Verification** | Desktop replay harness compiles the same C++ core and re-runs recorded rides byte-for-byte, so every engine change is A/B-scored in CI |
| **Paper** | Preprint on Zenodo — [doi.org/10.5281/zenodo.21115254](https://doi.org/10.5281/zenodo.21115254) |
| **Repository** | [github.com/morad-z/NavSight1](https://github.com/morad-z/NavSight1) |

Graded 100/100. The hardest problem I've worked on: state estimation where every sensor lies a little, and the filter has to find the truth between them.

</details>

<details>
<summary><code>02</code> <b>Skambil</b> — Multiplayer 36-card trick-taking game, playable with friends · <code>Live · 2026</code></summary>
<br/>

**A Briscola-family card game with one rules engine shared by server and bots, an authoritative WebSocket server, and a first-person 3D web client that holds no game logic.** The client is deployed on Netlify; the match server is self-hosted and brought up for game nights.

| Attribute | Details |
|:----------|:--------|
| **Stack** | C# / .NET (netstandard2.1) · ASP.NET Core WebSockets · TypeScript · React · Three.js · Vite · Docker |
| **Engine** | Dependency-free C# rules library; three bot tiers; `xorshift64*` determinism — seed + action log replays any match byte-for-byte |
| **Verification** | 24/24 spec vectors · 7/7 bot harness · **100,000-game fuzz** (every hand sums to exactly 120 points, 13,000 games/s) · 8/8 end-to-end server tests over four real WebSocket clients |
| **Security** | Per-seat filtered views — a reflection-based audit over a full match found **0 leaked cards**; rate limiting, sequence numbers, illegal-play rejection |
| **Server** | Private 5-character room codes, quick match with bot backfill, turn timers, disconnect grace with bot cover, reconnect with full resync |
| **Client** | Seated camera, held cards as real meshes with spring-physics throws; WebGPU or WebGL2 with an accessible HTML table as automatic fallback; Arabic · Hebrew · English, RTL-first |
| **Live** | [skambil.netlify.app](https://skambil.netlify.app) |

</details>

<details>
<summary><code>03</code> <b>XPlanner</b> — Worker shift & payroll system used by real accountants · <code>Production · 2025</code></summary>
<br/>

**Desktop app managing shifts, payroll, and labor compliance** — with a constraint engine enforcing real labor law (55-hour weekly cap, night-shift fatigue rules).

| Attribute | Details |
|:----------|:--------|
| **Stack** | TypeScript · React · Node.js · MongoDB · Electron · Jest · Vitest |
| **Scale** | Real-time multi-client sync via MongoDB Change Streams |
| **Performance** | Constraint engine validates schedules against compliance rules as they're built |
| **Security** | Auto-backups on exit and crash — no data loss in the field |
| **Impact** | **In production, used daily by accountants**; generates styled Excel reports |
| **Repository** | [github.com/morad-z](https://github.com/morad-z?tab=repositories) |

Built with Clean Architecture and the Repository Pattern, fully TDD — because payroll software has zero tolerance for bugs.

</details>

<details>
<summary><code>04</code> <b>B.H Nur</b> — Construction, fleet, fuel-logistics & payroll ops for a real family business · <code>Production · 2025 — 2026</code></summary>
<br/>

**Operations platform for a real construction business** — tracks invoices, expenses, fuel logistics, workers, vehicles, loans, and projects in one system.

| Attribute | Details |
|:----------|:--------|
| **Stack** | React · Node.js / Express · MongoDB · Electron · TailwindCSS · GitHub Actions |
| **Scale** | 20+ vehicles, fuel deliveries from 5+ depots, workers, parts, loans, projects — plus a role-based web portal where site managers report daily hours from their phones and the owner approves pay |
| **Performance** | Multi-destination fuel-transfer tracking with full audit logs |
| **Security** | Password-protected access; auto-backups; complete audit trail |
| **Impact** | **In daily production since 2025** — 66 tagged releases shipped through a GitHub Actions build-and-publish workflow and an in-app auto-updater; Hebrew Excel exports built for the accountants who use them |
| **Repository** | [github.com/morad-z](https://github.com/morad-z?tab=repositories) |

Born from inefficiencies I saw firsthand managing the family business — then engineered into software the business now runs on.

</details>

<details>
<summary><code>05</code> <b>TopGear</b> — Full offline garage-management system · <code>Production · 2026</code></summary>
<br/>

**A full offline, Hebrew RTL Tauri desktop app that runs an entire car garage** — no server, no subscription, no constant internet. Typing a license plate auto-fills make, model, year, and engine size from Israel's Ministry of Transport registry; a tabbed job flow then tracks parts, labor, and VAT and prints a legally-compliant tax invoice or 14-day price quote to PDF.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Tauri (Rust) · React · TypeScript · Dexie/IndexedDB · Zustand · TanStack Query · Tailwind CSS |
| **Scale** | Full quote → job lifecycle, appointments board, per-vehicle history, and profit aggregation by plate |
| **Performance** | Atomic transactional inventory — stock deduction/restore across the job lifecycle; instant local-first reads |
| **Security** | Code-signed in-place auto-updater; fully offline data ownership with JSON + CSV export/import |
| **Impact** | **In production**; license-plate registry API integration, client-side PDF generation, WhatsApp customer messaging from templates |
| **Repository** | [github.com/morad-z/TopGear](https://github.com/morad-z/TopGear) |

Local-first taken seriously: the garage owns its data, the app works with no connection, and updates ship signed.

</details>

<details>
<summary><code>06</code> <b>ZOBIDAT</b> — Avant-garde fashion site, scroll-pinned 3D WebGL lookbook · <code>Production · Live</code></summary>
<br/>

**A bespoke, motion-led brand website for an avant-garde fashion label** — a scroll-pinned 3D WebGL lookbook with custom GLSL shader atmospherics and a two-"world" art-directed scroll narrative.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Astro 5 · TypeScript · GSAP (ScrollTrigger/SplitText) · Lenis · OGL/WebGL · GLSL · Cloudflare Pages |
| **Scale** | Device-adaptive — GPU WebGL lookbook on desktop, touch-native CSS swipe deck on mobile |
| **Performance** | **Lighthouse 100 desktop / 88 mobile, 0 CLS** — AVIF/WebP pipeline cut backgrounds ~99%, textures ~90%; self-hosted subset fonts |
| **Security** | Full `prefers-reduced-motion` & accessibility support — focus trapping, semantic HTML, keyboard nav |
| **Impact** | Shipped on GitHub → Cloudflare Pages CI/CD with custom domain, automatic SSL, and content-hashed immutable caching |
| **Live** | [zobidat.com](https://zobidat.com) |

</details>

<details>
<summary><code>07</code> <b>Data Pipeline</b> — Serverless event-driven ETL on AWS · <code>Academic · 2025</code></summary>
<br/>

**Event-driven serverless pipeline:** S3 → SQS → Lambda → PostgreSQL with idempotent upserts, JSON schema validation, and a dead-letter queue for rejected records.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python · AWS S3/SQS/Lambda · PostgreSQL · Docker · LocalStack |
| **Scale** | Queue-driven design decouples ingestion from processing |
| **Performance** | Idempotent upserts guarantee safe replays |
| **Security** | JSON schema validation at every system boundary; DLQ isolates bad records |
| **Impact** | Fully reproducible local dev with Docker Compose + LocalStack before cloud deploy |
| **Repository** | [github.com/morad-z/data-pipeline-2025](https://github.com/morad-z/data-pipeline-2025) |

</details>

<details>
<summary><code>08</code> <b>Zoobar Red/Blue</b> — RCE chain vs. blockchain integrity ledger · <code>Security Research · 2026</code></summary>
<br/>

**Final project for Advanced Cyber — attack and detection in the same codebase.** Three real vulnerabilities chained against a privilege-separated web server, then caught by a custom integrity monitor.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python · C · Flask · SQLAlchemy · x86 Assembly · SHA-256 |
| **Scale** | Three chained CVE-class flaws across C parser, IPC socket, and ORM transfer logic |
| **Performance** | `POST /../../bin/sh` path traversal in the C URL parser → unauthenticated RCE |
| **Security** | World-writable microservice socket bypasses privilege separation; SQLAlchemy object-aliasing flaw mints money on self-transfers |
| **Impact** | A SHA-256 blockchain ledger hashes every legitimate transfer against the previous block — when the aliasing exploit mutates the DB, the ledger math breaks and the integrity monitor flags tampering |
| **Repository** | [github.com/morad-z/Advanced-cyber](https://github.com/morad-z/Advanced-cyber) |

Both sides of the exploit, end to end: how trust boundaries break, and how cryptographic integrity catches the break.

</details>

<details>
<summary><code>09</code> <b>Network Security Lab</b> — Layer-2 attack & defense, DHCP spoofing and ARP MITM · <code>Security Research · 2024</code></summary>
<br/>

**A closed-loop Layer-2 lab — attack and defense, demonstrated not just described.** Scapy scripts launch DHCP starvation, rogue-DHCP-offer, and ARP MITM traffic against isolated VMs; the same traffic is then blocked by the defense side.

| Attribute | Details |
|:----------|:--------|
| **Stack** | Python · Scapy · Wireshark · Linux VMs · DHCP Snooping · DAI |
| **Scale** | Repeatable multi-VM lab topology with scripted attack automation |
| **Performance** | Fully automated attack loop — no manual packet crafting |
| **Security** | Defenses applied and verified: DHCP Snooping, Dynamic ARP Inspection, port security |
| **Impact** | Every run is packet-captured in Wireshark so detection and mitigation are provable |
| **Repository** | [github.com/morad-z](https://github.com/morad-z?tab=repositories) |

</details>

<details>
<summary><code>10 — 13</code> <b>Archive</b> — Ray Tracer · Netflix Clone · Maze Generator · Connect Four · <code>Archived</code></summary>
<br/>

| # | Project | Stack | Description |
|:--|:--------|:------|:------------|
| `10` | **[Ray Tracer](https://github.com/morad-z/raytracer)** | C++ · OpenGL | Phong shading, hard shadows, spotlight cutoffs and checkerboard planes rendered from a scene file — Computer Graphics course |
| `11` | **[Netflix Clone](https://github.com/morad-z/netflix-clone-client)** | Node.js · React · MongoDB · JWT · TMDB | Full-stack streaming app with JWT auth, TMDB API integration, and an admin panel — deployed on Render |
| `12` | **[Maze Generator](https://github.com/morad-z/Maze-Generator-C-OOP-)** | C++ (OOP) · Algorithms | DFS/Prim maze generation with BFS/DFS solving, custom dimensions, save/load, and solver visualization |
| `13` | **[Connect Four](https://github.com/morad-z/Connect-4-game)** | Python · Sockets | Multiplayer game over raw TCP sockets with full win detection |

</details>

---

###### `03 / TOOLKIT`

## Toolkit

Stacks I've shipped production software with — from C++ over JNI to serverless pipelines on AWS.

#### Languages · `08`

<div align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,ts,js,kotlin,bash&theme=dark" alt="languages"/>
  <br/>
  <img src="https://img.shields.io/badge/SQL-cf7d08?style=flat-square&labelColor=070605&logo=postgresql&logoColor=f4f0e8" alt="SQL"/>
</div>

#### Backend & Data · `08`

<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,postgres,mysql&theme=dark" alt="backend and data"/>
  <br/>
  <img src="https://img.shields.io/badge/REST_APIs-95590a?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="REST APIs"/>
  <img src="https://img.shields.io/badge/JWT_Auth-b8690a?style=flat-square&labelColor=070605&logo=jsonwebtokens&logoColor=f4f0e8" alt="JWT"/>
  <img src="https://img.shields.io/badge/Socket.IO-cf7d08?style=flat-square&labelColor=070605&logo=socketdotio&logoColor=f4f0e8" alt="Socket.IO"/>
  <img src="https://img.shields.io/badge/Dexie_/_IndexedDB-e0930f?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="Dexie / IndexedDB"/>
</div>

#### Frontend & Desktop · `09`

<div align="center">
  <img src="https://skillicons.dev/icons?i=react,astro,electron,tailwind,vite,threejs,html,css&theme=dark" alt="frontend and desktop"/>
  <br/>
  <img src="https://img.shields.io/badge/Tauri_(Rust)-95590a?style=flat-square&labelColor=070605&logo=tauri&logoColor=f4f0e8" alt="Tauri"/>
  <img src="https://img.shields.io/badge/Jetpack_Compose-b8690a?style=flat-square&labelColor=070605&logo=jetpackcompose&logoColor=f4f0e8" alt="Jetpack Compose"/>
  <img src="https://img.shields.io/badge/GSAP-cf7d08?style=flat-square&labelColor=070605&logo=greensock&logoColor=f4f0e8" alt="GSAP"/>
  <img src="https://img.shields.io/badge/WebGL_/_GLSL-f5a21b?style=flat-square&labelColor=070605&logo=webgl&logoColor=f4f0e8" alt="WebGL / GLSL"/>
</div>

#### Systems & Vision · `08`

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,cmake,androidstudio&theme=dark" alt="systems and vision"/>
  <br/>
  <img src="https://img.shields.io/badge/OpenCV-cf7d08?style=flat-square&labelColor=070605&logo=opencv&logoColor=f4f0e8" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Android_NDK-95590a?style=flat-square&labelColor=070605&logo=android&logoColor=f4f0e8" alt="Android NDK"/>
  <img src="https://img.shields.io/badge/JNI_(C++_⇄_Kotlin)-b8690a?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="JNI"/>
  <img src="https://img.shields.io/badge/POSIX_·_Threads_·_Sockets-e0930f?style=flat-square&labelColor=070605&logo=linux&logoColor=f4f0e8" alt="POSIX"/>
</div>

#### Cloud & DevOps · `10`

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,cloudflare,git,github&theme=dark" alt="cloud and devops"/>
  <br/>
  <img src="https://img.shields.io/badge/AWS_S3_·_SQS_·_Lambda_·_RDS-cf7d08?style=flat-square&labelColor=070605&logo=amazonwebservices&logoColor=f4f0e8" alt="AWS services"/>
  <img src="https://img.shields.io/badge/LocalStack-e0930f?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="LocalStack"/>
  <img src="https://img.shields.io/badge/CI/CD-95590a?style=flat-square&labelColor=070605&logo=githubactions&logoColor=f4f0e8" alt="CI/CD"/>
</div>

#### Security & Networking · `05`

<div align="center">
  <img src="https://img.shields.io/badge/Wireshark-95590a?style=flat-square&labelColor=070605&logo=wireshark&logoColor=f4f0e8" alt="Wireshark"/>
  <img src="https://img.shields.io/badge/Scapy-b8690a?style=flat-square&labelColor=070605&logo=python&logoColor=f4f0e8" alt="Scapy"/>
  <img src="https://img.shields.io/badge/DHCP_/_ARP_Attacks-cf7d08?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="DHCP / ARP Attacks"/>
  <img src="https://img.shields.io/badge/Packet_Analysis-e0930f?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="Packet Analysis"/>
  <img src="https://img.shields.io/badge/MITM_Labs-95590a?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="MITM Labs"/>
</div>

#### Practices · `05`

<div align="center">
  <img src="https://img.shields.io/badge/TDD_·_Jest_·_Vitest_·_pytest-cf7d08?style=flat-square&labelColor=070605&logo=jest&logoColor=f4f0e8" alt="TDD"/>
  <img src="https://img.shields.io/badge/Clean_Architecture-95590a?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="Clean Architecture"/>
  <img src="https://img.shields.io/badge/Repository_Pattern-b8690a?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="Repository Pattern"/>
  <img src="https://img.shields.io/badge/DDD-e0930f?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="DDD"/>
  <img src="https://img.shields.io/badge/Code_Review-f5a21b?style=flat-square&labelColor=070605&logoColor=f4f0e8" alt="Code Review"/>
</div>

#### Proficiency

<div align="center">

| Domain | Proficiency | Details |
|:-------|:-----------:|:--------|
| **Offensive & Defensive Security** | `▓▓▓▓░ Advanced` | RCE chains (path traversal, privilege-separation bypass), SHA-256 blockchain integrity ledgers, DHCP/ARP attacks, DHCP Snooping & Dynamic ARP Inspection |
| **Computer Vision & State Estimation** | `▓▓▓▓░ Advanced` | Visual-inertial odometry (MSCKF/EKF), KLT feature tracking, IMU preintegration, zero-velocity updates — real-time 6-DOF pose on Android |
| **Production Desktop Engineering** | `▓▓▓▓░ Advanced` | Electron & Tauri (Rust) apps in daily production — transactional state, auto-backups, code-signed auto-updates, Excel reporting |
| **Backend & Systems Programming** | `▓▓▓▓░ Advanced` | Node.js/Express REST APIs, JWT auth, MongoDB Change Streams; C/C++ on Linux — POSIX, threads, sockets, JNI bridges |
| **Cloud & Event-Driven ETL** | `▓▓▓░░ Proficient` | AWS S3 → SQS → Lambda → PostgreSQL pipelines with idempotent upserts, DLQs, and LocalStack-based local dev |
| **Engineering Practices** | `▓▓▓▓░ Advanced` | TDD (Jest, Vitest, pytest), Clean Architecture, Repository Pattern, DDD, code review |

</div>

---

###### `04 / BACKGROUND`

## Background

### Manager — B.H. Nur Supermarket

`[ WHERE ]` Kiryat Tivon  ·  `[ WHEN ]` Jan 2017 – Aug 2020

Managed daily operations, staff training, inventory, and vendor relations — and identified the operational inefficiencies that I later solved by **building the XPlanner and B.H Nur software** now used in production.

- Led daily operations and trained staff; improved shift coverage and service consistency
- Managed inventory and vendor relations; reduced out-of-stock incidents through tighter ordering
- Turned firsthand operational pain into software requirements — then shipped the software

`Leadership · Operations · Inventory management · Team training · Product thinking`

<br/>

<div align="center">

<table>
<tr>
<td align="center"><code>[ AWARD ]</code><br/><br/><b>1st place — Forms UX Challenge</b><br/>Shenkar College</td>
<td align="center"><code>[ IN PRODUCTION ]</code><br/><br/><b>XPlanner · B.H Nur · TopGear</b><br/>Used daily by accountants and business operators</td>
</tr>
<tr>
<td align="center"><code>[ VOLUNTEER ]</code><br/><br/><b>חינוך לפסגות · Education for Excellence</b><br/>With Bank Hapoalim · teacher hours tracked in Tandemwise</td>
<td align="center"><code>[ LANGUAGES ]</code><br/><br/><b>Arabic · Hebrew · English</b><br/>Native · fluent · fluent</td>
</tr>
</table>

</div>

---

###### `05 / CURRENT FOCUS`

## Current focus

```yaml
current_focus:
  learning:
    - Visual-inertial odometry & state estimation (MSCKF/EKF)
    - Offensive & defensive security — exploit chains, integrity monitoring
    - Distributed systems & cloud architecture patterns

  building:
    - Skambil — multiplayer card game: C# rules engine, ASP.NET Core WebSocket server, Three.js client
    - B.H Nur — site-manager hours portal and payroll approvals
    - Production desktop apps with Electron & Tauri (Rust)

  exploring:
    - Rust for systems & desktop development
    - Real-time 3D / WebGL experiences (Three.js · GLSL)

  open_to:
    - Cyber / Security Engineering
    - Full-Stack & Backend Engineering
    - Platform / Systems roles (junior & new-grad)

  degree: "B.Sc. Software Engineering — Shenkar College, 2026 · final project graded 100/100"
```

---

###### `06 / GITHUB ACTIVITY`

## GitHub activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=morad-z&show_icons=true&hide_border=true&bg_color=070605&title_color=ffba4d&icon_color=f5a21b&text_color=9d968a&ring_color=f5a21b&include_all_commits=true&count_private=true" height="180" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=morad-z&layout=compact&hide_border=true&bg_color=070605&title_color=ffba4d&text_color=9d968a&langs_count=8" height="180" alt="top languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=morad-z&hide_border=true&background=070605&ring=f5a21b&fire=ffba4d&currStreakLabel=ffba4d&sideLabels=9d968a&currStreakNum=f4f0e8&sideNums=f4f0e8&dates=9d968a" alt="streak stats"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=morad-z&bg_color=070605&color=9d968a&line=f5a21b&point=f4f0e8&area=true&area_color=7a4708&hide_border=true" width="100%" alt="contribution activity graph"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/morad-z/morad-z/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/morad-z/morad-z/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/morad-z/morad-z/output/github-contribution-grid-snake-dark.svg" alt="contribution snake"/>
</picture>

</div>

---

###### `07 / CONTACT`

## Contact

<div align="center">

`● TRACK COMPLETE ───────────────── DEST · 32.79°N 34.98°E · HAIFA`

<br/>

`[ Let's build something that stays up ]`

<br/><br/>

<a href="mailto:contact@moradz.dev">
  <img src="https://img.shields.io/badge/Email-contact@moradz.dev-f5a21b?style=for-the-badge&labelColor=070605&logo=gmail&logoColor=f4f0e8" alt="Email"/>
</a>
<br/>
<a href="https://www.linkedin.com/in/morad-zubedat/">
  <img src="https://img.shields.io/badge/LinkedIn-in%2Fmorad--zubedat-e0930f?style=for-the-badge&labelColor=070605&logo=linkedin&logoColor=f4f0e8" alt="LinkedIn"/>
</a>
<br/>
<a href="https://github.com/morad-z">
  <img src="https://img.shields.io/badge/GitHub-morad--z-cf7d08?style=for-the-badge&labelColor=070605&logo=github&logoColor=f4f0e8" alt="GitHub"/>
</a>
<br/>
<a href="https://www.moradz.dev">
  <img src="https://img.shields.io/badge/Portfolio-moradz.dev-b8690a?style=for-the-badge&labelColor=070605&logo=googlechrome&logoColor=f4f0e8" alt="Portfolio"/>
</a>

<br/><br/>

`© Morad Zubedat — built in Haifa` · `Open to junior & new-grad roles`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7a4708,20:241505,55:0d0a07,100:070605&height=140&section=footer" width="100%" alt="footer banner"/>

</div>
