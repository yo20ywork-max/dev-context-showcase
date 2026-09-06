# Development Context & Handoff

[Portfolio](https://github.com/yo20ywork-max/research-portfolio) · [Project map](https://github.com/yo20ywork-max/research-portfolio/blob/main/PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/dev-context`.

## Problem

Work spread across repositories and computers can lose context: which repository owns a feature, what changed, and what another session should read first.

## My implementation work

Establishing a versioned handoff and project-index workflow for ongoing software development.

## Technical scope

- A small Git-backed context repository.
- Durable decisions separated from disposable local caches.
- Project ownership and repository/deployment relationship records.
- A review process for public documentation and private operational material.

## Evidence and current scope

This public case describes the engineering method. The operational memory file remains private because it contains internal configuration and development history.

## Relationship to other work

Supporting engineering infrastructure used alongside the application projects. It is represented as process work, rather than a separately shipped customer product.

## Engineering perspective

Documenting sources of truth and handoff rules helps make iterative, AI-assisted development inspectable and repeatable across sessions.

For the public/private boundary, see [Public Disclosure Scope](DISCLOSURE.md).

## Public repository contents

This repository is the public presentation of the source project identified above. See [Evidence and technical scope](EVIDENCE.md) for the material included here. It is not an additional product or a replacement for the operational source repository.
