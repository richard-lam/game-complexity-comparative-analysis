# Project cEDH Research Papers

**Richard Lam — 2026**

Research papers and demonstrations for Project cEDH — an initiative exploring competitive Magic: The Gathering as a benchmark for strategic intelligence in artificial systems.

Motivated by the recognition of Magic: The Gathering as the world's most complex game by the *MIT Technology Review*, this body of work provides a comparative framework for understanding strategic depth across perfect- and imperfect-information systems, and proposes competitive Elder Dragon Highlander (cEDH) as a candidate benchmark for evaluating broader forms of AI decision-making.

---

## Repository Structure

```
.
├── whitepapers/
│   ├── Chess_vs_Go_vs_Magic_Comparative_Complexity/   # Whitepaper 1
│   └── The_Project_cEDH_Framework/                    # Whitepaper 2
├── demo/
│   ├── demo001/   # MTG Game Engine + AI (slide deck)
│   └── demo002/   # cEDH AI Platform (slide deck)
└── README.md
```

---

## Whitepapers

### 1. Chess vs Go vs Magic: The Gathering — A Comparative Complexity Analysis

Compares the cognitive and strategic demands of Chess, Go, and Magic: The Gathering across multiple dimensions — including information structure, decision type, game state size, and skill requirements. Highlights why MTG, particularly in the cEDH format, presents a uniquely challenging environment combining combinatorial complexity, hidden information, probabilistic reasoning, and constantly evolving metas.

| Aspect | Chess | Go | Magic: The Gathering |
|---|---|---|---|
| Information | Perfect | Perfect | Imperfect |
| Game State Size | ~10^47 | ~10^170 | Effectively unbounded |
| Decision Type | Deterministic | Deterministic | Probabilistic, adaptive |
| Time to Master | Decades | Lifelong | Lifelong; evolving meta |

Available in six languages:

- [English](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_EN.pdf)
- [French](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_FR.pdf)
- [German](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_DE.pdf)
- [Italian](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_IT.pdf)
- [Spanish](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_ES.pdf)
- [Japanese](whitepapers/Chess_vs_Go_vs_Magic_Comparative_Complexity/Chess_vs_Go_vs_Magic_Comparative_Complexity_JP.pdf)

### 2. Magic: The Gathering as a Benchmark for Strategic Intelligence in Artificial Systems — The Project cEDH Framework

Proposes competitive Magic: The Gathering (cEDH) as a candidate AI benchmark that integrates imperfect information, stochastic dynamics, symbolic rule interactions, multi-agent competition, and an evolving strategy space within a single environment. Introduces Project cEDH, a deterministic simulation framework supporting reproducible experimentation with AI agents. Includes a mathematical framing of decision complexity and a three-stage experimental methodology (baseline heuristic agents, self-play training, and human evaluation).

| Game | Information | Agents | Rule Space |
|---|---|---|---|
| Chess | Perfect | 2 | Fixed |
| Go | Perfect | 2 | Fixed |
| Poker | Imperfect | 2–6 | Fixed |
| cEDH | Imperfect | 3–4 | Expanding |

Available in six languages:

- [English](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_EN.pdf)
- [French](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_FR.pdf)
- [German](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_DE.pdf)
- [Italian](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_IT.pdf)
- [Spanish](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_ES.pdf)
- [Japanese](whitepapers/The_Project_cEDH_Framework/The_Project_cEDH_Framework_JP.pdf)

---

## Demos

### demo001 — MTG Game Engine + AI

[View PDF](demo/demo001/MTG_game_engine_AI.pdf)

Slide deck presenting the architecture and current state of the full competitive MTG game engine. Covers:

- **Software Architecture** — Frontend (React + TypeScript, Vite + Tailwind) → FastAPI REST API → Game Controller → Core Rules Engine
- **Data Model** — GameState, Player, GameObject, Card, Decklist, and DeckBuilder entities with Scryfall card data integration
- **Core Engine** — Turn & priority system, stack resolution & counterspells, mana costs (hybrid, phyrexian, X), multiplayer combat, triggers, abilities, keywords, and oracle text execution
- **End-to-End Gameplay** — Game creation from decklists, Commander London Mulligan, full turn cycle, spell casting & stack interaction, combat, triggers, state-based actions, and AI auto-pass priority

### demo002 — Magic: The Gathering cEDH AI

[View PDF](demo/demo002/Magic_%20the_Gathering-CEDH_AI.pdf)

Slide deck showcasing the cEDH AI platform with full UI demonstrations. Includes the landing page, multiplayer game lobby creation (human + AI slots), quick-game mode against AI opponents, mulligan decision interface, and in-game board state with card tooltips, game log, stack viewer, and zone management.

---

## Multilingual Editions

All whitepapers are provided in six languages aligned with official Magic: The Gathering localization standards: **English**, **French**, **German**, **Italian**, **Spanish**, and **Japanese**.

---

## Planned Work

- Deterministic multiplayer game state modeling
- Human-in-the-loop gameplay systems
- Multi-agent decision making under imperfect information
- Heuristic evaluation and Monte Carlo Tree Search
- Self-play training infrastructure
- Negotiation, trust, and reputation modeling in adversarial environments

---

## Author

Richard Lam — Independent Researcher
