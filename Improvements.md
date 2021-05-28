# Improvements over untuned results

These tables show the improvement over the baselines as a percentage. The better of random and hyperopt is used for tuned results. A negative value indicates a performance drop.

## Bunch

|           | BCP | ICP | SM   | MQ   | IFN |
|-----------|-----|-----|------|------|-----|
| jpetstore | 0%  | 0%  | 0%   | 0%   | 0%  |
| plants    | 24% | 9%  | -23% | 21%  | 18% |
| daytrader | 6%  | 11% | -37% | -59% | 4%  |
| acmeair   | -5% | 7%  | 0%   | 7%   | 0%  |

## CO-GCN

|           | BCP   | ICP  | SM  | MQ   | IFN  |
|-----------|-------|------|-----|------|------|
| jpetstore | -36%  | 38%  | 19% | -66% | 10%  |
| plants    | 20%   | 96%  | 42% | -17% | 78%  |
| daytrader | -114% | 97%  | 50% | -46% | 74%  |
| acmeair   | 13%   | 100% | 36% | -10% | 100% |

## FoSCI

|           | BCP | ICP | SM   | MQ  | IFN |
|-----------|-----|-----|------|-----|-----|
| jpetstore | 21% | 94% | 0%   | 40% | 81% |
| plants    | 15% | 87% | 266% | 26% | 43% |
| daytrader | 30% | 94% | 71%  | 22% | 81% |
| acmeair   | 20% | 90% | 100% | 25% | 68% |

## MEM

|           | BCP  | ICP  | SM   | MQ  | IFN  |
|-----------|------|------|------|-----|------|
| jpetstore | -2%  | -2%  | -4%  | 20% | 11%  |
| plants    | 0%   | 100% | 52%  | 6%  | 100% |
| daytrader | 3%   | -55% | -18% | 50% | -10% |
| acmeair   | -11% | 100% | -22% | -7% | 100% |
