# Educators — HYPAR_ELEMENTS

**Project:** HYPAR_ELEMENTS  
**Category:** ARCHITECTURAL_DESIGN  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1954f665d0f3d9b9c4b656b0d3d7d337208f3a604246c6aa3063c3eb6ffbe81a`  
**Date:** October 2026

## Teaching with HYPAR_ELEMENTS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `1954f665d0f3d9b9c4b656b0d3d7d337208f3a604246c6aa3063c3eb6ffbe81a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
