# How to Contribute

## Submitting a pull request

### Forked strategy

This repository managed based on forked pull request strategy.

```sh
# Fork this repository to yours.
$ git clone [YOUR_REPOSITORY_URL]
$ cd scanner-cache

# (Working...)

$ git commit [...]
$ git push origin [YOUR_REPOSITORY]

# Enroll pull-request!
# in https://github.com/sonaractions/scanner-cache
```

## Commit message rules

Each commit message consists of a **header**, a **body** and a **footer**.
The header has a special format that includes a **type**, a **scope** and a **subject**:

```text
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### Type

Must be one of the following:

- **feat**: When create a new feature.
- **fix**: When fix a bug.
- **docs**: When add or change documentation.
- **style**: When improve code style.
- **refactor**: When improve code without add or change feature.
- **perf**: When improve performance.
- **test**: When add or change test code.
- **chore**: When change build process or tool.
- **revert**: When revert a commit.
- **misc**: When something else entirely.

### Scope

The scope could be anything specifying place of the commit change.
For example `deps-dev`, `workflows`, etc...

### Subject

The first part of the commit message begins with an infinitive, and the first letter is capitalized.
It starts with commands such as `Fix`, `Add` and `Change` instead of past tense such as `Fixed`, `Added`
and `Changed`. In addition, It does not exceed 72 characters and does not end with a period (.).

- `Fixed` -> `Fix`
- `Added` -> `Add`
- `Changed` -> `Change`

