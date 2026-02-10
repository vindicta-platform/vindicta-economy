> **Part of the [Vindicta Platform](https://github.com/vindicta-platform)**

# Vindicta Economy

Ledger, Quotas, and Gas Tank for the Vindicta Platform.

## Installation

```bash
uv sync
```

## Features

- **Atomic Ledger**: Immutable transaction history for platform credits.
- **Gas Tank**: Predictive billing and quota management.
- **Achievements**: Platform-wide achievement and reward system.

## Testing & Coverage

```bash
uv run pytest --cov
uv run behave
```
Coverage Mandate: ≥90%

## Docs

- [Models Reference](docs/models.md)
- [API Reference](../Vindicta-API/README.md)
