# Security Policy

## Reporting a vulnerability

Please report security problems privately through
[GitHub's private vulnerability reporting](https://github.com/unchidev/tailwind-with-cielab/security/advisories/new).
Do not open a public issue for them.

We will reply within 7 days to confirm that we received your report, and keep you updated until it is fixed.

## Supported versions

Only the `main` branch receives security fixes.

## What counts as a vulnerability

- Script injection through the sample page
- A change to a third-party asset the page loads (CDN files) that is not covered by its integrity hash
- A vulnerable dependency that is reachable from the sample
