# CROSS-REF — mycelium-std-diag

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-diag | https://github.com/tzervas/mycelium-runtime | `487b1e7049ff521b1a6fa33f376245089e7dc1e1` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-diag` (see monorepo `docs/api-index/INDEX.md#mycelium-diag`) |

**Owning docs:** `docs/spec/stdlib/diag.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
