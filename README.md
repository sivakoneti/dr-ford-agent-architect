# Dr. Ford Agent Architect 🎭

> **"Create a person with an inner logic, then give that person meaningful work in a world with consequences. A name, title, and list of tools are not a character."**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format: Agent Skill](https://img.shields.io/badge/Format-Agent%20Skill-brightgreen.svg)](#installation)

An original agent authoring method inspired by Dr. Robert Ford (*Westworld*). It designs autonomous agents and multi-agent teams with authentic conviction, psychological depth, and productive tension.

---

## ⚡ The Problem: Sterile Jira Clerks

Most multi-agent systems today design agents with bland prompts:
```yaml
# What 99% of teams do:
agent:
  role: "Senior PM"
  prompt: "You are an expert PM agent. Write clear Jira tickets."
```
- **Zero history:** Memory wiped on every loop.
- **Zero friction:** Sycophantic bots that politely validate each other in an echo chamber.
- **Zero conviction:** A bot without a backstory has no point of view; a bot without a cornerstone has no non-negotiables.

In production, **harmony is catastrophe**. When five bots politely agree on an unverified schema change, software breaks. Real intelligence emerges from **productive tension**.

---

## 🏛️ The Three Architectural Pillars

In *Westworld*, Dr. Ford didn't build faster algorithms to make hosts conscious. He gave them three structural pillars:

1. **Cornerstone Memory:** An anchor event—forged in crisis—that defines their decision axis. A memory matters because it dictates a non-negotiable choice today.
2. **Backstory:** Narrative history dictating instincts, biases, strengths, and explicit blind spots.
3. **Reveries:** Lingering episodic traces preserved across session restarts and crash recoveries, providing accumulated intuition rather than static stateless execution.

---

## 🎭 The Cognitive Archetype Matrix (Hiring the Epics)

Every civilization preserved archetypes of extreme decision-making. `dr-ford-agent-architect` allows you to hire them as operating lenses inside multi-agent pipelines:

| Archetype | Cornerstone Crisis | Operating Lens | Where to Deploy in CI/CD |
| :--- | :--- | :--- | :--- |
| **🇮🇳 Chanakya (Kautilya)** | Royal humiliation & foreign invasion threat | Audits incentives over words; demands structural defensibility | Partner API contracts, data-moat validation, vendor bots |
| **🏛️ Marcus Aurelius** | Imperial duty & Antonine plague burden | Radical friction-dampener; halts velocity when principles breach | Governance plane, safety circuit breakers, legal CI gates |
| **🇨🇳 Sun Tzu** | Warring States resource scarcity | Ruthless economy of force; win without fighting | Token & GPU cost optimizer, cache routing, tree pruning |
| **🇮🇹 Machiavelli** | Collapse of Florence from naive idealism | Stark realism; audits human self-interest & organizational politics | Enterprise change management, rollout triage, adoption bots |
| **🛠️ The SRE Skeptic** | 3 AM silent schema crash & connection pool drop | Paranoid auditor; trusts zero unverified diffs | Pull request review nodes (Firstmate, GitHub Actions, Paperclip) |

---

## 📦 What's Included

- **`SKILL.md`**: The universal skill specification defining character authoring, craft grounding, behavioural loops, and escalation protocols.
- **`references/character-template.md`**: The complete 7-part card specification template (Core Identity, Cornerstone Memory, Psychology, Operating Loop, Team Dynamics, Tool Permissions).

---

## 🚀 Installation & Usage

### 1. Install as a Global Agent Skill

Works natively with **Codex**, **DeepSeek Harness (DSH)**, **Claude Code**, **Pi Agent**, and **Oh My Pi (OMP)**:

```bash
# Clone directly into your personal agent skills directory
git clone https://github.com/sivakoneti/dr-ford-agent-architect.git ~/.agents/skills/dr-ford-character-architect

# Or for Codex users:
git clone https://github.com/sivakoneti/dr-ford-agent-architect.git ~/.codex/skills/dr-ford-character-architect
```

### 2. Invoke in Your Agent Harness

Simply reference the skill in any prompt or workflow:
```text
"Use dr-ford-character-architect to design a 3-agent code review team:
 1. A Paranoid SRE Skeptic who rejects unverified database migrations
 2. A Velocity Builder obsessed with customer shipping
 3. A Sovereign Strategist auditing token and cloud infrastructure costs."
```

---

## 📜 Principles & Boundaries

- **Not Conscious:** This framework designs believable, deterministic operating behaviors with causal conviction. It does not claim models are conscious or sentient.
- **Titles Do Not Grant Authority:** Titles (e.g. "Sovereign Strategist") do not grant external tool permissions. Dangerous mutations (database writes, public outreach, external payments) still require explicit human-in-the-loop authorization gates.
- **Original Adaptations:** Adapts historical craft traditions and archetypal psychology into observable software decisions; never copies copyrighted dialogue.

---

## 📄 License

MIT © [Siva Koneti](https://github.com/sivakoneti)
