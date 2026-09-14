# Mission: Pi (terminal coding harness)

## Why
Adopt Pi as a daily-driver terminal coding agent alongside/in place of current tools (heavy Claude-Code-style usage today). The goal is fluency good enough that switching over doesn't cost speed on real work.

## Success looks like
- Install, authenticate, and run Pi on a real project without referring to docs
- Comfortable with core interactive commands, session management (branching, `/tree`, `/fork`, `/clone`, compaction), and settings
- Can install and use existing Skills/Extensions/Prompt Templates/Packages, and knows how to write a basic one
- Understands the trust/sandboxing model well enough to use it safely on real repos
- Knows the specific places Pi's behavior/philosophy diverges from Claude Code (no built-in MCP, sub-agents, plan mode, permission popups, to-dos, background bash) so nothing is a surprise mid-task

## Constraints
- Learning happens alongside daily work — lessons should be short and immediately applicable
- Already fluent with the general shape of terminal coding agents (slash commands, context files, sessions, tool-calling loop) — skip conceptual intros to that category, focus on Pi's specifics and deltas

## Out of scope (for now)
- SDK / RPC mode / JSON event stream mode (programmatic integration) — not the current goal
- Building/publishing Pi Packages for others to consume
- Platform-specific setup beyond Linux (Windows, Termux, tmux)
- llama.cpp local model routing
