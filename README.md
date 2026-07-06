# HKG33 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-43_999_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full HKG33 dataset on ork.ad**](https://ork.ad/)

**HKG33 1h OHLCV Stock index historical data** — ultra high-quality 1h OHLCV for **Hong Kong 33**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **Hong Kong 33** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **43,999** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `HKG33_1h.csv` (3,015 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **43,999** `1h` rows (~2.6 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-09-11` → `2026-07-03`.

## Download sample

**[HKG33_1h.csv](https://github.com/ork-ad/hkg33-1h-ohlcv-index-historical-data/blob/main/HKG33_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/hkg33-1h-ohlcv-index-historical-data/main/HKG33_1h.csv)) · [GitHub Releases](https://github.com/ork-ad/hkg33-1h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/hkg33-1h-ohlcv-index-historical-data/](https://ork-ad.github.io/hkg33-1h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Hong Kong 33 · Stock index | Hong Kong 33 · Stock index |
| Timeframes | `1h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1h rows | 3,015 | **43,999** |
| Size | 0.18 MB | ~2.6 MB |
| Period | `2025-10-03` → `2026-07-03` | `2008-09-11` → `2026-07-03` |
| File | `HKG33_1h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`HKG33_1h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T18:00:00Z | 27068.09 | 27123.59 | 27037.07 | 27119.08 | 6721.0 |
| 2025-10-06T01:00:00Z | 27119.08 | 27160.17 | 26948.63 | 27074.15 | 27050.0 |
| 2025-10-06T02:00:00Z | 27074.15 | 27091.64 | 26911.12 | 26941.64 | 19060.0 |
| 2025-10-06T03:00:00Z | 26941.64 | 26988.63 | 26887.13 | 26976.14 | 7323.0 |
| 2025-10-06T05:00:00Z | 26976.14 | 27006.15 | 26873.13 | 27005.14 | 6392.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T14:00:00Z | 23239.04 | 23243.56 | 23211.56 | 23232.56 | 1876.0 |
| 2026-07-03T15:00:00Z | 23232.56 | 23241.55 | 23197.56 | 23211.06 | 1616.0 |
| 2026-07-03T16:00:00Z | 23211.06 | 23219.56 | 23204.04 | 23215.56 | 952.0 |
| 2026-07-03T17:00:00Z | 23215.56 | 23221.54 | 23210.04 | 23213.05 | 364.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('HKG33_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('HKG33_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('HKG33_1h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **HKG33** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **43,999** rows at `1h`, plus all other timeframes in the same ZIP.

**[→ Get the full HKG33 dataset on ork.ad](https://ork.ad/)**

---
*GetData · HKG33 1h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*