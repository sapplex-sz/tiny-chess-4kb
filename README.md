# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sapplex-sz/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/sapplex-sz/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

n7 is a 10x12 string-board engine: tapered PeSTO evaluation and alpha-beta with a transposition table, PVS, reverse futility pruning, null move, LMR, killers and history, quiescence, and repetition draws. It searches a fixed 150000 nodes per move (6e7 per trial), deterministic, with no clock and the Python standard library only. `main.py` is that source packed with the kit's `makefun compress` (LZMA).

Local practice trial-0: 5/6, slowest move 1.79 s.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

## Build

Edit `engine.py`, then repack with `makefun compress engine.py --out main.py`.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
