## v0.29 to v0.30 Genesis Conversion

One-time magic port script to convert a Cosmos SDK `v0.29.x` state export into a Cosmos SDK `v0.30.x`-compatible genesis file.

[Python 3](https://python.org) required.

Usage:

```bash
# gaiad export --for-zero-height > export.json
# ./v0.29-to-v0.30.py export.json genesis.json
```

To add vesting accounts, run:

```bash
# ./add-vesting.py genesis.json genesis_vesting.json
```
