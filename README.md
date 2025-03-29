# Write Meaningful Commit Messages

### Commit Message Structure

A well-structured commit message typically consists of three parts:
* **Header:** A brief summary of the changes (50-72 characters).
* **Body:** Detailed explanation of the changes, reasoning, and any background information (wrapped at 72 characters).
* **Footer:** Any references to issues, tickets, or breaking changes

Example

```sh
Header: Short summary of the commit (50-72 characters)

Body: Detailed explanation of the changes, reasons behind them, and any
important background context. Wrap text at 72 characters. Explain why the
changes were necessary and how they solve the problem.

Footer: References to issues, e.g., "Fixes #1234". Mention any breaking changes.
```

### Common Commit Message Types

* **feat** : A new feature.
* **fix** : A bug fix.
* **docs** : Documentation only changes.
* **style** : Changes that do not affect the meaning of the code (white-space, formatting, etc.).
* **refactor** : A code change that neither fixes a bug nor adds a feature.
* **perf** : A code change that improves performance.
* **test** : Adding missing or correcting existing tests.
* **chore** : Changes to the build process or auxiliary tools and libraries.
