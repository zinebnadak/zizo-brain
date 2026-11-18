# Conventions

## Code
- Python, typed, with small functions and clear names.
- Constants for magic numbers (prices, paths) at the top of the file.
- Handle missing files and bad input without crashing.

## Git
- One commit = one idea. Every commit is a working state.
- Commit messages: `feat:`, `fix:`, `test:`, `docs:`, `refactor:`.
- Never commit `.env` or secrets.

## Quality
- Think about tests, cost and security, never only "does it run".
- Every new function gets at least one pytest test.

## Safety
- Propose, never act. Running commands, writing files and pushing need my approval.
