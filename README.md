# 🦉 ONode

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **ONode** — Owl Network Diagnostic Suite ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ONode is a network diagnostic suite (ORecon) for DNS resolution, TCP port scanning, SSL/TLS certificate info, ping, reverse DNS, local network/route/ARP views, CIDR calculation, IP classification, and TCP latency probes. Results can be written as JSON; colour output is optional.

---

## ✨ Features

- DNS resolution (A/AAAA plus dig-style records) and reverse DNS / PTR lookup
- TCP port scan with configurable port list; SSL/TLS certificate inspection
- ICMP ping and TCP connect latency probe with configurable port
- Local network info, routes, and ARP/neighbour tables
- Offline CIDR/subnet calculator and IP classification
- Optional JSON result file via `--json-out`; `--no-color` for plain output

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ONode --dns example.com
./ONode --scan 192.168.1.10 --ports 22,80,443
./ONode --ssl example.com --json-out result.json
./ONode --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
