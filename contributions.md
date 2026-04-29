---
layout: page
title: My Open Source Contributions
permalink: /contributions/
---

<!--
Type of the contribution should be "Wikipedia edit", "OpenStreet Map feature", "Documentation", "Course website", "Blog",
"Browser Add-on", etc.

The description should include a brief summary of what you did.

The link should bring us to a public page that shows your contribution. 

Replace the first row with your own contribution. 

-->





| Date #       | Contribution (Link)  | Type  | Description |
|---|:---|:---|:---|
| Feb 3   | link to my contribution    | course website    |   I fixed a broken link.    |
| Apr 23   | [Arkworks Issue](https://github.com/arkworks-rs/algebra/issues/920)    | Documentation / Discussion    |   Participated in a discussion about how to define the degree of the zero polynomial. I shared my thoughts on the trade-off between correctness and simplicity, and suggested using `Option<usize>` to better handle edge cases.   |
| Mar 15 – Apr 23   | [Groth16 PR #91](https://github.com/arkworks-rs/groth16/pull/91)    | Documentation    |   Improved documentation across five core modules (`lib.rs`, `data_structures.rs`, `prover.rs`, `verifier.rs`, `r1cs_to_qap.rs`) in the arkworks Groth16 zkSNARK library. Added crate-level overview with quick-start example, documented mathematical formulas for proof elements A/B/C, explained the pairing verification equation, annotated the 7-step FFT-based QAP witness map, and expanded field-level docs for all proving/verifying key data structures.   |
| Apr 28   | [Plonky3 Issue #1581](https://github.com/Plonky3/Plonky3/issues/1581)    | Performance / Discussion    |   Participated in a discussion on a performance regression in Goldilocks field arithmetic on Neon. I analyzed the trade-off between packed SIMD multiplication and addition performance, and raised questions about the impact of reduced packing width (2 → 1). I also suggested evaluating real-world zk workloads (e.g., FFT, polynomial operations) to better understand the practical impact of the regression.   |
| Apr 28   | [Transformers PR #45687](https://github.com/huggingface/transformers/pull/45687)    | Performance / Systems Discussion    |   Contributed to a discussion on dtype selection for histogram computation across heterogeneous hardware (CUDA vs MPS). I examined the performance vs portability trade-off (int vs float histograms) and questioned the real-world impact on MoE workloads. I also proposed a fallback strategy (try int → fallback to float) and discussed how failure predictability should influence design decisions.   |
