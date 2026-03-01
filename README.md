# Sable

**Sable** is a high-performance streaming parser for large forensic and telemetry files.

Built for security researchers, DFIR analysts, and infrastructure engineers who are tired of:
- memory-heavy scripts
- tools that crash on large files
- slow JSON processing
- format-specific utilities

Sable parses massive structured files, normalizes artifacts into a unified schema, and makes them queryable from the CLI.

---

## Why Sable?

Modern security workflows involve:
- Multi-GB forensic exports
- CloudTrail dumps
- Browser history files
- SIEM exports
- Large JSON datasets

Most tooling:
- Loads entire files into memory
- Breaks on edge cases
- Is format-locked
- Is difficult to extend

Sable is:

- ⚡ Streaming-first (no full memory load)
- 🧩 Plugin-based
- 🗃 Normalized output schema
- 🖥 CLI-native
- 🧠 AI-optional (never required)

---

## Installation

```bash
go install github.com/sgr0691/sable@latest
