# Contradiction-First-Loop

A TRIZ-based thinking layer for design, development, and vibe-coding. It sits before you generate code or mockups: it turns a task into a contradiction and an ideal, then diverges along a deck of proven moves, so you dissolve a trade-off instead of shipping a generic middle-ground compromise.

Built for people who design interfaces or build with AI and keep getting results that "work" but feel templated.

Why it exists

AI generation is strong at production and weak at framing. Ask for a screen and you get a plausible, generic answer, usually shaped as a compromise. This loop hits that gap: it names the tension before you generate, and turns that same tension into an acceptance test after, so a generic draft has nowhere to hide.

It is not a replacement for design craft, research, or JTBD. It is the "how do I resolve this once I know the problem" step, and it's deliberately lightweight.

What you get
A 5-move procedure — contradiction → ideal → resources → diverge → generate & check.
The 4 separations — the flagship tool for "simple vs powerful" interface dilemmas.
A full deck — all 40 TRIZ principles translated into dev / UI / vibe-coding language, grouped by symptom.
A validation gate — a 6-point pass/fail run before anything moves downstream. No empty runs.
A handoff pipeline — where JTBD / design thinking feed in, and where ux-copy / humanizer take over.
Two worked examples and a competitive map vs SCAMPER, brainstorming, TRIZ, and others.
Repo structure
SKILL.md                              core procedure, gate, pipeline, best practices
README.md                             this file
README-ru.md                          Russian reading copy of the skill
references/
  deck.md                             all 40 principles → product language
  example.md                          two full runs (dashboard, onboarding)
  competitive-analysis.md             positioning map + head-to-head
How to use it
Open SKILL.md.
Fill the Input Brief for your task (task in one line, current state, the tension, users, constraints, definition of "good").
Run the 5 moves.
Pass the validation gate.
Generate, then hand off to copy / humanizer, then ship.

Run it standalone by default. Bridge to JTBD, systems thinking, Lean, or ADR only when there's a real gap to close.

If you use Claude skills or a similar setup, drop this folder in as a skill and it will trigger on trade-off and "simplify without losing power" style requests. Otherwise it reads fine as a plain method doc.

Status

Early and honest. I've run it on a handful of my own interface and architecture problems. It works best on genuine forks and is overkill on trivial screens. Feedback and pull requests welcome, especially where it breaks.
