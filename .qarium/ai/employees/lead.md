# Lead

## Architecture & Decisions
- **setuptools-scm for versioning** — version is derived from git tags, eliminating manual version bumping
- **Optional dependency groups** — test, dev, docs separated for minimal installation footprint
- **ruff as unified linter/formatter** — replaces flake8, isort, black with single fast tool

## Project Structure
- **Source in qarium/** — main package directory with same name as project
- **No src/ layout** — package directly in project root (flat layout)

## Code Patterns
- **Line length 100** — configured in ruff, wider than PEP 8 default
- **Ruff rules: E, F, W, I, UP, B** — pycodestyle errors, Pyflakes, warnings, isort, pyupgrade, flake8-bugbear

## TODO
<!-- empty -->

## LLM Directives
<!-- empty -->