# Commit Message Conventions

This document outlines the conventions for writing commit messages in the **FasIBP** repository. Following these conventions will help maintain a clear and consistent project history.

## Commit Message Structure

A commit message should follow this format:
<type>[optional scope]: <description>
[optional body]
[optional footer]

### Types of Commits

Use the following types for your commits:

- **feat**: A new feature (e.g., `feat: add user authentication`)
- **fix**: A bug fix (e.g., `fix: resolve crash on login`)
- **docs**: Documentation changes (e.g., `docs: update README`)
- **style**: Formatting changes that do not affect code meaning (e.g., `style: format code`)
- **refactor**: Code changes that neither fix a bug nor add a feature (e.g., `refactor: simplify user model`)
- **test**: Adding or correcting tests (e.g., `test: add unit tests for user service`)
- **chore**: Changes to the build process or auxiliary tools (e.g., `chore: update dependencies`)

### Example Commit Messages

Here are some examples of well-formed commit messages:

feat(auth): implement user login
This commit adds the login functionality with validation for username and password.

fix(ui): correct button alignment on login page
The login button is now properly aligned to the center of the page.

docs: update installation instructions in README
