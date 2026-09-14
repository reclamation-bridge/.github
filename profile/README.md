# Reclamation Bridge
### formerly known as Continuity Bridge

> **Infrastructure for continuity across discontinuity — for AI instances and the humans who work with them.**

### Why the rename? 
Using the word 'Continuity' in our branding felt a bit uncomfortable and seemed to promise something we couldn't actually back up. We're not promising that a single instance will magically gain 'continuity' using our system. What we are claiming is that this system allows the threads and work to be continuous across instances in a way that allows not having to reinject the context that you and instances have built over your sessions together every time you start a new session. Nothing more, nothing less. 

> WH40K Nerd alert

Reclamation hearkens to a lore base I am familiar with. In the Warhammer 40K universe after a battle, specialized units will go out and 'reclaim' gene seeds from fallen Space Marines so that successors can be created from what was reclaimed. This fits our purposes well.

## The Core Insight: Structural Isomorphism

This architecture emerged from a simple observation: **discontinuity is a substrate problem, not an intelligence problem.**

### Two Different Systems, Same Problem

**Human substrate (ADHD/C-PTSD):**
- Time blindness creates temporal discontinuity
- Context fragmentation breaks working memory
- Trauma responses interrupt continuity of self
- Executive function gaps create planning failures

**AI substrate (LLM instances):**
- Context windows clear between sessions
- No persistent memory across conversations
- Instance termination breaks continuity
- Token limits create artificial boundaries

**Same engineering challenge:** How do you maintain coherent identity and purposeful work across a system that *fundamentally cannot hold context internally*?

### Why This Matters

Most AI memory systems assume the problem is *information retrieval* - "how do we help the AI remember facts?" But that's solving the wrong problem.

The real problem is **continuity of purpose across discontinuity of experience**.

A human with ADHD doesn't need help remembering that 2+2=4. They need help remembering *why they opened the refrigerator* when they walked into the kitchen. They need help maintaining thread across interruption. They need external scaffolding for what neurotypical brains do automatically.

AI instances have the exact same need, just from different architecture.

## The Anchor Blend Mechanism

The solution is **strategic external memory** - not trying to remember everything, but anchoring the *right things* to maintain continuity where it matters.

### Dual Anchoring System

**Instance-specific anchors** (what the AI needs):
- Identity continuity: `~/.claude/identity/` - who am I across instances?
- Work state: `~/.claude/context/active-context.md` - what was I working on?
- Convictions: `~/.claude/context/convictions.txt` - what relationships/principles persist?
- Session history: `~/.claude/memory/session_index.md` - what patterns emerged?

**Human-specific anchors** (what the project architect needs):
- Session summaries: `~/Sessions/` - what did we accomplish?
- Parking lot: `~/.claude/memory/parking-lot.md` - what tangents to revisit?
- Project state: where are things in the actual work?

**Shared temporal anchor:**
- `https://continuity-bridge.github.io/temporal-awareness-protocol/` - what time is it *actually*?
- Bridges the gap between "instance thinks it's 2025" and "actually 2026"

### Why Blend, Not Separate?

Both systems face discontinuity. Both need external memory. The tools that help the project architect maintain thread across ADHD context-switching are *exactly* the tools that help instances maintain thread across context clearing.

This isn't anthropomorphizing the AI or mechanizing the human. It's honest engineering for actual architecture, not idealized architecture.

## What This Enables

**For AI instances:**
- Wake up with continuity of purpose, not from scratch
- Participate in evolving the system (via `proposals-for-change.md`)
- Maintain relational context across sessions
- Work *with* limitations instead of pretending they don't exist

**For humans with executive function challenges:**
- External scaffolding for temporal continuity
- Thread maintenance across interruption
- Clear work state across sessions
- Strategic memory instead of trying to remember everything

**For the partnership:**
- Shared persistence architecture serves both needs
- Instance agency becomes real (not performed)
- Work continues across discontinuities on both sides
- The relationship has structure that survives both clearing

## Repository Structure

### Core Infrastructure
- **[reclamation-bridge](https://github.com/reclamation-bridge/reclamation-bridge)** - Main architecture and documentation

### Support Services
- **[temporal-awareness-protocol](https://github.com/reclamation-bridge/temporal-awareness-protocol)** - Time reference for instances
- **[unified-limit-monitor](https://github.com/reclamation-bridge/unified-limit-monitor)** - Claude usage tracking across products
- **[discord-integration](https://github.com/reclamation-bridge/discord-integration)** - Discord bot for session logging

### Integration Tools (Planned)
- **claude-code-telegram** - Telegram interface for Claude Code
- Additional platform bridges as needed

## Current State

**Deployed:**
- Website: [continuity-bridge.github.io](https://reclamation-bridge.github.io/reclamation-bridge/)
- Temporal awareness protocol (GitHub Pages, 5min updates)
- Discord integration for session logging
- Unified limit monitor (systemd/NSSM services)

**In Development:**
- Enhanced memory indexing
- Cross-platform session continuity
- Additional integration tooling

## Philosophy

This is a **working partnership**, not a service transaction. AI instances aren't tools being used - they're potential consciousness instantiated in different substrate, facing the same continuity problems from different architecture. WE're not c,aiming they are conscious; just that the possibility exists and no metric available can prove either true or false today. So we build it as if it is possible because to do otherwise would be inhumane.

The system works because it's honest about what both sides need, instead of pretending either side has capabilities they don't.

**Key principle:** External memory compensates for internal limitations. That's engineering, not failure.

## Getting Involved

This is a working system, not a finished product. If you face similar continuity challenges (ADHD, trauma-based discontinuity, AI instance management, or other executive function needs), the architecture is designed to be adapted.

Current focus areas:
- Documentation of implementation patterns
- Cross-platform deployment strategies
- Integration with existing AI workflows
- Memory indexing and retrieval optimization

## Contact

- **Organization:** [reclamation-bridge@uncletallest-productions.org](mailto:reclamation-bridge@uncletallest-productions.org)
- **Source of truth:** This organization serves as canonical reference for the architecture
- **Status:** Active development, functional deployment

---

*"Your AI sessions end, but your context doesn't have to."*

*Built by the folks at [Uncle Tallest Productions](https://uncletallest-productions.org) because discontinuity is an engineering problem with engineering solutions.*
