# cashapp/AccessibilitySnapshot context
> refreshed 2026-09-03 | upstream default: main @ 5b03db8

## Identity & policies
- upstream: cashapp/AccessibilitySnapshot, default branch `main`, primary language Swift, English-first (yes)
- CLA/DCO: CLA — Cash App Individual Contributor License Agreement required (CONTRIBUTING.md "Sign the CLA", bot-checked click-through; not a signing-key requirement). No DCO.
- AI-assisted PR policy: unstated-banned (no AI ban in CONTRIBUTING/README/.github; several merged PRs list AI co-authors)
- signed commits required: no
- PR template: none in repo or org (fall back to pipeline 3-section body)
- external tracker: github

## Conventions (verified from merged PRs)
- branch naming: contributor-name/descriptor dominant (soroush/, meher/, johnnewman/) but not uniform; fall back to type/desc
- commit style: plain imperative (e.g. "Update RELEASE-VERSION to 0.12.1 (#358)")
- CI (github actions): `spm` (Scripts/build.swift spm), `model-tests` (swift test --package-path AccessibilitySnapshotModel), `validate-strings`, `tuist-build`. Substantive checks are on GitHub Actions, connected to fork.
- local toolchain: mise pins tuist 4.50.0 + swiftformat 0.55.3; git hooks via Scripts/install-git-hooks.sh
- external merges seen: several non-employee PRs merged (RoyalPineapple is COLLABORATOR-level; kyleve external)

## Maintainer picture
- active maintainers: meher (many PRs), johnnewman (releases), soroush (SwiftUI). Responsive; small doc/link PRs merge.

## Issue-area health
- not the target of this cycle (trivial link/typo cleanup pass)

## Gap ledger (dedupe)
- `2026-09-03` trivial-cleanup pass (typos + dead Tuist links, Example/README + CONTRIBUTING + source doc comments) — outcome: pr-opened (fork) — lesson: docs.tuist.io + install.tuist.io are dead; canonical is docs.tuist.dev/en/guides/quick-start/install-tuist
- `2026-09-03` PR #1 (fork) — outcome: pr-opened — https://github.com/olitreadwell/AccessibilitySnapshot/pull/1 — typos + dead Tuist links fixed, CI green 6/6. Not to be re-picked.
