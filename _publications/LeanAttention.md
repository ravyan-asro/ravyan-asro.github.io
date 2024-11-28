---
title: "LeanAttention"
collection: publications
category: conferences
permalink: https://arxiv.org/abs/2405.10480
excerpt: 'LeanAttention is an attention execution mechanism that provides near 100% GPU occupancy for any problem size during attention while delivering more than 2x speedups for ragged batching and decoding scenarios.'
date: 2024-05-01
paperurl: 'https://arxiv.org/pdf/2405.10480'
---
LeanAttention is a scalable and energy-efficient technique of computing self-attention for ragged batching scenarios and the token-generation phase (decode-phase) of decoder-only transformer models. By extending the "stream-K" style reduction of tiled calculation to self-attention, we enable parallel computation with well-balanced loads during attention, resulting in an average of 2.6x attention execution speedup over FlashAttention-2 and up to 8.33x speedup for 512k context lengths.