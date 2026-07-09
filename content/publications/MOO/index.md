---
title: "Automatic Selection of the Best Neural Architecture for Time Series Forecasting"
authors:
  - "Qianying Cao"
  - "Shanqing Liu"
  - "Alan John Varghese"
  - "Jérôme Darbon"
  - "Michael S. Triantafyllou"
  - "George Em Karniadakis"
date: "2026-06-02"
publication: "Nature Communications"
publication_types:
  - "article-journal"
doi: "10.1038/s41467-026-73687-9"
featured: true
---

Time series forecasting is essential across domains such as healthcare, energy, and climate modeling. While models like LSTMs, GRUs, Transformers, and State-Space Models (SSMs) have become widely used, selecting the optimal architecture remains unclear. We propose an automated framework that systematically designs hybrid architectures by combining LSTM, GRU, attention, and SSM modules. Our approach uses multi-objective optimization to explore combinations and orderings of blocks, yielding Pareto-optimal architectures that balance user-defined trade-offs among objectives. A preference function selects the most suitable model for a given application. Moreover, two sampling-based iterative procedures for Pareto-front exploration are introduced, which reduces the total training cost by nearly eightfold. 
