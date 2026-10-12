# PTA Tracker

**A playful time-off tracker built for a teammate. It logs hours, warns before the yearly limit, and shows the "impact" of each day away, all with a login, calendar and request flow.**

[Live demo](https://piperintech.github.io/PTAtracker/)

---

## What it does

- **Balance:** hours used vs. a yearly allowance, with an on-track status
- **Request flow:** pick a date range → hours are calculated automatically → submit
- **Over-limit guardrail:** if a request would exceed the allowance, it shows the overage and asks for a make-up commitment before it goes through
- **Calendar and history:** time off and holidays at a glance, with a full record log
- **Impact overview:** a tongue-in-cheek report on how each hour away affects the team

## Why I built it

A fun side build that started as a team joke. It was also a quick way to practice a complete small product: auth screen, state, validation rules, edge cases, and a polished UI in one file.

## Stack

Single-file HTML/CSS/JavaScript · browser `localStorage` for state · GitHub Pages

> The login is a front-end demo only and doesn't protect real data.

---

Built by **Manuela Gonzalez Piper** · Product & AI · [GitHub](https://github.com/piperintech)
