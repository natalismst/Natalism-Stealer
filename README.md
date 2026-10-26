div align="center">

# NATALISM

### The operator-grade steal & control ecosystem — agent, delivery, panel, and a built-in RAT in one stack.

[![Panel](https://img.shields.io/badge/Panel-panel.cryptowtf.info-white?style=for-the-badge)](https://panel.cryptowtf.info)
[![Discord](https://img.shields.io/badge/Discord-@natalismstealer-000039?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/natahook)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://panel.cryptowtf.info)

<br/>

**Collect. Deliver. Control. Repeat.**

</div>

---

## The pitch

Most tooling in this space stops at the grab — a zip, a webhook, and a lot of hope. **Natalism is a full loop**, not a single script. A hardened Java agent pulls the data, a routing layer pushes it wherever you want it, a modern panel keeps the whole operation organized, and a native control channel lets you drive the box live — no second product required.

> One agent. One panel. One pipeline. Nothing bolted on afterwards.

**What you actually get**

| Layer | What it does |
|-------|--------------|
| **Agent** | Java 17, JNA, obfuscated build. Browsers, Discord, backup codes, screenshot, archive. |
| **Delivery** | Discord webhook embeds + per-account cards + the raw archive. Custom hook routing. |
| **Control** | Live screen, remote filesystem, shell, processes, clipboard, power, dialogs, chat, on-demand re-grab. |
| **Platform** | Next.js panel, Discord build bot, license + seat management, WAF + OTP auth. |
| **Formats** | `JAR`, `EXE` (custom icon + label), and a **Forge mod jar** for Minecraft delivery. |

---

## Collection

### Browsers

Chromium engines and Gecko, full-profile extraction on every run.

| Engine | Targets |
|--------|---------|
| **Chromium** | Chrome · Edge · Brave · Vivaldi · Opera · Opera GX · Yandex · Chromium |
| **Gecko** | Mozilla Firefox (all profiles) |

**What gets pulled per profile**

- **Passwords** — every profile, formatted, with top-password and email highlights
- **Cookies** — Netscape format, session-ready
- **History & autofill** — complete browsing data
- **Saved cards** — Chromium payment methods
- **Downloads** — per-browser download history

### Beyond browsers

- **Discord tokens** — multi-location scan across the desktop client, Chromium stores, Firefox, IndexedDB and session storage
- **Discord enrichment** — live API lookup: account identity, email, phone, billing, subscriptions, friends, guilds
- **Backup code scanner** — filesystem sweep across Desktop, Documents, Downloads, Pictures and OneDrive, matching dozens of platforms by name and content
- **Screenshot** — desktop capture on each run
- **Archive** — everything lands in an organized `natalism-stealer.zip`

---

## Remote control

The agent carries a full control channel over a signed WebSocket. Open a machine from the panel and drive it.

| Channel | Capability |
|---------|------------|
| **Screen** | Live stream, mouse + keyboard injection, zoom, pan, quality presets |
| **Files** | Browse, upload, download, delete, mkdir — full remote filesystem |
| **Shell** | Remote command execution |
| **Processes** | Enumerate and kill |
| **Clipboard** | Read / write |
| **Power** | Shutdown, restart, logoff, lock, sleep |
| **Dialogs** | Custom Windows-style alert prompts, sticky or timed |
| **Chat** | Live two-way dock with the target |
| **Re-grab** | Trigger a fresh collection on demand |

Auto-reconnect with backoff, signed handshake, and a single persistent channel per host.

---

## The panel

A modern **Next.js** operator console at [panel.cryptowtf.info](https://panel.cryptowtf.info).

- **Dashboard** — live stats, per-day activity graph, recent hits
- **HWID list** — every connected box, online status, one-click control
- **Control** — the full RAT surface with tabbed navigation
- **Logs** — steal history with archive download
- **Build center** — JAR / EXE / Forge builds with custom label, icon, staged progress
- **Keys & seats** — license and reseller management
- **Users** — roles for staff (full admin or approver-only)
- **Audit** — event trail

**Auth** — license key with one-time verification. **Edge** — reverse proxy, WAF, rate limiting, per-hook routing.

---

## Build formats

| Format | Notes |
|--------|-------|
| **JAR** | Lightweight, runs on Java 17+ |
| **EXE** | Custom icon + filename, wrapped runtime |
| **Forge mod** | Drop-in Minecraft mod jar — loads inside the game, self-extracts and runs |
| **DLL** | Windows DLL loader — loaded via rundll32, regsvr32, or injection; it downloads, extracts, and runs the program. |

The Forge artifact is a real mod: it loads through Minecraft, extracts the payload at runtime, and executes it independently of the game.

---

## FAQ

**Is this a rebrand of something else?**
No — the agent, panel, bot and build pipeline are one codebase, built to work together.

**Do I need a separate RAT?**
No. Remote control ships with the agent: screen, files, shell, processes, clipboard and more.

**Which build should I use?**
JAR for light delivery, EXE for a custom icon and filename, Forge when the target runs Minecraft.

**How does the Forge build work?**
It's a genuine mod jar. Minecraft loads it, and at runtime it extracts and runs the payload on its own.

**How do I get a key?**
Join [discord.gg/natahook](https://discord.gg/natahook) and ask the admins for a trial, or buy a full license in-channel.

**How does auth work?**
A license key paired with one-time verification — no shared, reusable passwords.

**Can I resell?**
Seat keys are available for licensed resellers — contact the admins on Discord.

---

## Links

| | |
|---|---|
| **Panel** | [panel.cryptowtf.info](https://panel.cryptowtf.info) |
| **Discord** | [discord.gg/natahook](https://discord.gg/natahook) |
| **Build bot** | Discord — `/build` commands |

---

<div align="center">

**NATALISM** — *collect · deliver · control*

<br/>

`Java agent` · `Discord pipeline` · `remote control` · `Next.js panel` · `Forge build`

<br/>

© 2026 Natalism

</div>