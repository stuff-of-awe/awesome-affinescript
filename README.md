<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome AffineScript

A small, curated starting point for learning and evaluating [AffineScript](https://github.com/hyperpolymath/affinescript), a language whose implementation and documentation are still evolving. This collection is a **starter**, not a claim that every planned compiler feature works. Use the project’s capability and soundness records to check current support before adopting it.

**Reviewed:** 6 November 2026 · **Initial curator:** Jonathan D.A. Jewell (`hyperpolymath`) · **Scope:** AffineScript-specific learning, reference, examples, and community resources. All initial entries come from the AffineScript author’s repositories; independent contributions are welcome and will be assessed on the same terms. Links were checked for existence on the review date. The examples below were **not executed** for this list.

## Start here

- [AffineScript source and overview](https://github.com/hyperpolymath/affinescript) — compiler repository and project orientation; start here to see the current architecture and release context.
- [Hello-world lesson](https://github.com/hyperpolymath/affinescript/blob/main/docs/tutorial/lesson-01-hello.adoc) — first guided program for a new reader. Check the capability matrix if the lesson and current compiler disagree.
- [Tutorial sequence](https://github.com/hyperpolymath/affinescript/tree/main/docs/tutorial) — lessons on functions, data, patterns, types, errors, effects, generics, modules, and building.

## Current capability and design

- [Capability matrix](https://github.com/hyperpolymath/affinescript/blob/main/docs/CAPABILITY-MATRIX.adoc) — authoritative per-feature implementation state; read this before relying on a feature.
- [Soundness record](https://github.com/hyperpolymath/affinescript/blob/main/docs/SOUNDNESS.adoc) — known proof and implementation gaps for readers assessing safety claims.
- [Compiler capabilities reference](https://github.com/hyperpolymath/affinescript/blob/main/docs/reference/COMPILER-CAPABILITIES.adoc) — a more detailed guide to what the compiler accepts and emits.
- [Language specification](https://github.com/hyperpolymath/affinescript/blob/main/docs/specs/SPEC.adoc) — design reference; a specification can describe planned behaviour as well as implemented behaviour.

## Explore examples

- [Faces examples](https://github.com/hyperpolymath/affinescript/blob/main/examples/faces/README.adoc) — examples of the language’s different surface syntaxes for readers comparing the same idea across faces.
- [Extension-boundary consumer](https://github.com/hyperpolymath/affinescript/blob/main/examples/consumers/extension-boundary/README.adoc) — a host integration example to inspect; execution has not been verified for this list.
- [Road-skate prototype](https://github.com/hyperpolymath/affinescript-vite) — an AffineScript driving-game experiment. Its own README calls it a prototype and lists missing game features.

## Community and contributions

- [AffineScript discussions](https://github.com/hyperpolymath/affinescript/discussions) — ask questions and discuss language design.
- [AffineScript issues](https://github.com/hyperpolymath/affinescript/issues) — implementation reports and feature work.
- [Contributing to the compiler](https://github.com/hyperpolymath/affinescript/blob/main/.github/CONTRIBUTING.md) — project-specific contribution rules.
- [Suggest an addition to this list](CONTRIBUTING.md) — send useful AffineScript-specific resources, including independent projects, tutorials, and critiques.

This list curates links; it does not maintain the linked software. Maturity and affiliation labels describe the linked source as checked, not an endorsement or independent audit. Collection text is [CC BY-SA 4.0](LICENSES/CC-BY-SA-4.0.txt); linked projects retain their own licences.
