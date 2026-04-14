# CLAUDE.md — PestPro 2.0

## Project Overview

PestPro 2.0 is a pest control management application. This is a greenfield project — the repository is being built from scratch.

## Repository Status

This repository is in its initial setup phase. There is no existing codebase yet. Contributors (human or AI) should follow the conventions below when building out the project.

### Current Tree

```
pestpro_2.0/
└── CLAUDE.md   # This file
```

No source code, `package.json`, tests, CI, or configuration files exist yet. The tech stack has not been chosen.

### Active Branches

- `claude/add-claude-documentation-ax0st` — documentation branch (current). Contains the initial commit introducing `CLAUDE.md`.
- `main` does not yet exist. It should be created from the first meaningful commit once a tech stack is chosen.

## Development Conventions

### Git Workflow

- **Main branch:** `main` (to be created with the first meaningful commit)
- **Feature branches:** Use the pattern `claude/<description>-<session-id>` for AI-assisted work
- **Commit messages:** Use clear, descriptive messages. Lead with a verb in imperative mood (e.g., "Add user authentication", "Fix scheduling bug")
- **Push:** Always use `git push -u origin <branch-name>`

### Code Style

- Keep code simple and readable
- Prefer explicit over implicit
- Avoid over-engineering — build only what is needed now
- Add comments only where logic is non-obvious

### File Organization

Follow standard conventions for whichever framework is adopted:
- Keep source code in `src/` or framework-standard directories
- Keep tests alongside source files or in a `tests/` directory
- Store configuration at the project root
- Use `.env.example` for environment variable documentation (never commit `.env`)

### Testing

- Write tests for business logic and critical paths
- Run the full test suite before pushing

### Security

- Never commit secrets, API keys, or credentials
- Validate all user input at system boundaries
- Follow OWASP best practices

## Key Commands

_(To be filled in as the tech stack is established)_

```bash
# Install dependencies
# TBD

# Run development server
# TBD

# Run tests
# TBD

# Lint / format
# TBD
```

## Architecture

_(To be documented as the application takes shape)_

### Planned Domain Areas

- **Customers:** Client management
- **Scheduling:** Appointment and route management
- **Services:** Pest control service definitions and tracking
- **Billing:** Invoicing and payment processing
- **Technicians:** Staff management and assignments

## Notes for AI Assistants

- Always read existing files before modifying them
- Prefer editing existing files over creating new ones
- Run tests after making changes when a test suite exists
- Do not add unnecessary abstractions or premature optimizations
- When unsure about a design decision, ask the user

## Session History

This log tracks AI-assisted sessions so future sessions can pick up where prior ones left off. Each session should append a short entry when it finishes meaningful work.

### 2026-04-14 — `claude/add-claude-documentation-ax0st`

- Initial repository bootstrap. Repository was completely empty (no commits, no files) at the start of the session.
- Created the feature branch `claude/add-claude-documentation-ax0st`.
- Added `CLAUDE.md` with project overview, git workflow, code style, security, planned domain areas, and notes for AI assistants.
- Extended `CLAUDE.md` with a current-tree snapshot, active-branch list, and this session-history log.
- Commits on branch: `Add CLAUDE.md with project conventions and structure guidelines` (root commit).
- Outstanding decisions for future sessions: choose a tech stack (frontend framework, backend language/runtime, database), establish test and lint tooling, create `main`, and fill in the Key Commands / Architecture sections below as they are decided.
