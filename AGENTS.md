# AGENTS.md

Operating notes for AI coding agents (Claude Code, Codex, Cursor, Copilot and others) working in this repository. Everything here is derived from the files actually in the tree, so trust it over guesses, and update it when the facts change.

## What this repository is

Three-dimensional recursive spatial subdivision.

- Homepage: https://w-moomsi.vercel.app
- Source: https://github.com/nirholas/-w-.---
- Primary language: JavaScript
- License: Other (see the LICENSE file)

## Repository layout

- `src/`
- `test/`
- `README.md`
- `LICENSE`
- `package.json`

Tests live in `test/`. Add or update a test next to the code you change.

## Setup

```bash
yarn install
```

## Commands

| Task | Command |
|---|---|
| test | `yarn test` |

Run the test and lint commands above before you consider a change finished. If a command fails on code you did not touch, say so in your report instead of silently skipping it.

## Conventions

- Read the surrounding code before adding to it, and match its naming, file organisation and error-handling style.
- Keep `README.md` accurate: if a change alters behaviour, commands or configuration, update the docs in the same commit.
- Do not leave TODO comments, stub functions, placeholder data or commented-out code behind. Finish what you start or leave it out.
- Small, focused commits with a subject line that describes the change, not the act of committing.

## Where to raise things

- Bugs and feature requests: https://github.com/nirholas/-w-.---/issues
- Questions and ideas: https://github.com/nirholas/-w-.---/discussions
- Security issues: report privately at https://github.com/nirholas/-w-.---/security/advisories/new, never in a public issue.
