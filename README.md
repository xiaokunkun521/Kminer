<p align="center">
  <img src="assets/kminer_logo.png" width="130" alt="Kminer logo">
</p>

<h1 align="center">Kminer</h1>

<p align="center"><b>High-performance native NVIDIA miner for Pearl (PRL)</b></p>

---

## Overview
Kminer 是基于CUDA驱动API开发的高性能NVIDIA显卡挖矿程序，专为 Pearl（PRL / PearlHash）算法优化。
程序架构轻量化，CPU占用极低，内置各代显卡专属优化内核，启动自动匹配硬件，发挥显卡最优算力。
闭源二进制分发，原生适配 HiveOS。

## HiveOS 使用方式
1. 新建自定义矿工工作表单
3. 钱包模板填写：`%WAL%.%WORKER_NAME%`

| Generation | Cards |
|---|---|
| **Blackwell** (RTX 50) | 5090 · 5080 · 5070 Ti · 5070 · 5060 Ti · 5060 · 50-series Laptop |
| **Hopper** | H100 · H200 — Pearl, Cryptix, QubitCoin *(no card on hand to verify; Xelis and BTX are not built for this generation)* |
| **Ada** (RTX 40) | 4090 · 4080 (S) · 4070 Ti (S) · 4070 (S) · 4060 Ti · 4060 · 40-series Laptop |
| **Ampere** (RTX 30) | 3090 Ti · 3090 · 3080 Ti · 3080 · 3070 Ti · 3070 · 3060 Ti · 3060 · 30-series Laptop |
| **Turing** (RTX 20) | 2080 Ti · 2080 (S) · 2070 (S) · 2060 (S) · 20-series Laptop *(driver 545+)* |
| **Volta** | Tesla V100 |
| **Pascal** | GTX 10-series · P102-100 · P104-100 · P106 · P108 (mining cards) |
| **CMP** | 90HX · 50HX · 40HX · 30HX *(driver 545+)* |
