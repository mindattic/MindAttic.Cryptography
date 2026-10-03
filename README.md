# MindAttic.Cryptography

Planned .NET library of cryptographic helpers shared across the MindAttic ecosystem. Not built yet: the repository holds only agent scaffolding, no library code.

![.NET](https://img.shields.io/badge/.NET-library-512BD4) ![Status](https://img.shields.io/badge/status-placeholder-lightgrey)

## Status

MindAttic.Cryptography is a placeholder. There is no project file, no source and no package yet. Its purpose, per the repository description, is to be a shared home for cryptographic helpers used by other MindAttic libraries and apps.

One extraction has already been tried. [MindAttic.Authentication](https://github.com/mindattic/MindAttic.Authentication) once moved its Argon2id password hashing, PHC string handling, TOTP and secret resolution into a standalone MindAttic.Cryptography package, then reverted that change; those primitives still live inside MindAttic.Authentication today. Its README records the details.

What is here today:

| Path | Purpose |
| --- | --- |
| `AGENTS.md` | Points coding agents at the shared MindAttic agent standard |
| `.prose/commands/` | Portable aliases (commit, do, progress, quickload, quicksave, show) that call the shared agent runner |
| `.claude/` | Client settings: a context-usage status line and the quicksave and quickload hooks |
| `.gitignore` | Ignores the local quicksave transcript |

## Roadmap

Planned, not started:

- Create the .NET class library project.
- Decide which primitives move here, starting with the candidates from the earlier MindAttic.Authentication extraction.

There is nothing to install or run yet.

## Documentation

- [AGENTS.md](AGENTS.md) — agent entry point for this repository.

## License

No license file. All rights reserved.

Part of [MindAttic](https://mindattic.com) — see more projects at [github.com/mindattic](https://github.com/mindattic). Related: [MindAttic.Authentication](https://github.com/mindattic/MindAttic.Authentication).
