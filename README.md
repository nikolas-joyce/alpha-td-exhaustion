# alpha-td-exhaustion

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-td-exhaustion/blob/main/notebooks/alpha_td_exhaustion.ipynb)

> TD Exhaustion alpha signal

> DeMark's original exhaustion signal: 9 consecutive closes each lower than the close four bars prior (bull setup) or higher (bear setup), filtered by the TDST level. Completion signals that a move has gone too far and a reversal is probable. This notebook focuses on the standalone exhaustion signal, its sensitivity to setup count, and how it compares to the broader TD Sequential suite.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | TD Sequential engine |
| 4 | L5/S5 signal generation |
| 5 | Returns & performance |
| 6 | Per-ticker breakdown |
| 7 | Parameter sensitivity (setup count, TDST window) |
| 8 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

