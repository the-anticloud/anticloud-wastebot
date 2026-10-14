# Educators — WASTEBOT

**Project:** WASTEBOT  
**Category:** WASTE_MANAGEMENT  
**Upstream:** https://github.com/al4224t/wastebot  
**Pinned commit:** `4296f4ad8a4789a175a690120d8f2273beeefabf`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a9f4fa47805832f4804684b50d33c53104f1c6ce49a1c802f46a94d9401b4154`  
**Date:** October 2026

## Teaching with WASTEBOT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a9f4fa47805832f4804684b50d33c53104f1c6ce49a1c802f46a94d9401b4154` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
