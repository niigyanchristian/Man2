

# Project Standards — Man2

## 1. Project Overview

Man2 is a newly initialized project that currently contains only a `README.md` file. No source code, configuration files, dependencies, or build tooling have been established yet. The project has no determinable tech stack, framework, or runtime at this time.

This document serves as a **foundational standards template** to be updated as the project takes shape. Any contributor (human or AI) adding the first meaningful code to this repository **must** update this document to reflect the chosen stack and conventions.

## 2. Tech Stack & Versions

**Not yet established.** When the first code is added, this section must be updated with:

- Programming language and version
- Framework (if any) and version
- Package manager and lockfile strategy
- Runtime environment
- Bundler / build tool (if applicable)

## 3. Code Conventions

Until source code exists, the only applicable conventions are:

- **Documentation files:** Use Markdown (`.md`) format.
- **Line endings:** Use LF (`\n`), not CRLF.
- **File naming:** Use `UPPER_CASE` for repo-level documentation files (e.g., `README.md`, `CONTRIBUTING.md`, `LICENSE`).

## 4. Architecture Patterns

No architecture has been established. When code is introduced, document:

- Folder/module structure
- State management approach (if applicable)
- API communication patterns (if applicable)
- Error handling strategy

## 5. Known Inconsistencies & Resolutions

None — the project contains no code to conflict.

## 6. Anti-Patterns (Do NOT do these)

- **Do NOT** add source code without first establishing and documenting the tech stack in this file.
- **Do NOT** commit dependency artifacts (e.g., `node_modules/`, `venv/`, build output) to the repository. Set up a `.gitignore` before adding any tooling.
- **Do NOT** leave this standards document in its current skeleton state once the project has real code. It must be updated in the same PR that introduces the foundational stack.