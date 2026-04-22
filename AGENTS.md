# OpenAPI Development

This directory is a git submodule. The source of truth is `openapi.yaml`.

## Rules

- Use `pnpm` for local scripts and dependency management.
- Keep schema changes minimal and aligned with current behavior.
- All `/internal/v1` endpoints are beta.
- Lint with `pnpm lint`.
- Preview with `pnpm serve`.
- If schema changes affect generated Go clients or MCP code, run `task generate:uptraceapi` from the repo root.
