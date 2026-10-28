# FoldMate Pricing & Cost Laboratory (Mission 3)

A static, local-first interactive pricing and unit-economics lab for the proposed FoldMate residential clothes-folding appliance. It is an educational decision workspace, not a forecast or a recommendation engine.

## Run locally

Serve this folder with any static HTTP server and open its root URL. No build step, backend, API key, external runtime library, or account is required. Google Fonts are an optional visual enhancement; the app runs with system fonts if those fonts are unavailable. Model edits are stored in this browser's `localStorage` only. JSON config import/export and confirmed decision report downloads are local browser actions.

## Inputs and evidence

`competitor_data.json` is the full Mission 1 pricing research snapshot dated 2026-10-27. It preserves distinct competitor units and includes all sourced offers, classifications, and limitations. The live page highlights representative machine, manual-aid, and service references; it does not blend those unlike units.

Research cost references in the app link to BLS May 2025 mechanical-engineer wages, current Stripe card pricing, Shopify pricing, and USPTO trademark fees, checked on 2026-10-27. Published prices are reference benchmarks. Product manufacturing, shipping, insurance, compliance, warranty, and startup figures are editable illustrative placeholders because the design, channel, supplier quotes, and test data are not established.

The original venture website URL was not supplied in the setup or found in the supplied Mission 1/2 project files. The app records it as unavailable instead of guessing.

## GitHub Pages

This project is published from the `main` branch root; enable Pages in repository Settings → Pages → Deploy from a branch → `main` / `/(root)`. No build workflow is required.

## Privacy and decision gate

The static site has no analytics or submission endpoint. Model inputs remain in browser storage. The report is enabled only after the user marks a review current, writes a justification, acknowledges both review notes, and confirms the exact snapshot. Any edit clears that confirmation. Downloaded DOCX and JSON are generated from the same frozen snapshot and are not uploaded.
