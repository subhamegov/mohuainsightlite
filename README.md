# MoHUA Urban DPI Prototype

**From fragmented urban records to connected, evidence-based decision-making.**

A standalone demonstration of how shared identifiers and interoperable urban registries can connect mission delivery, municipal services, investments and grievances. It presents different decision views for MoHUA, state urban development departments and city administrators using the same underlying synthetic records.

## What it demonstrates

- **National view:** Cross-mission convergence, fund release status and state-level rollups.
- **State view:** City comparisons and conditions associated with programme funding.
- **City view:** Operational measures, cross-system dependencies and a unified grievance-routing demonstration.
- **Convergence map:** Schematic ward-level PMAY-U, AMRUT 2.0 and SBM-U 2.0 layers, linked to a housing-block registry record.
- **Decision brief:** Prioritised actions, projects requiring decisions, delays, dependencies and printable briefing content.
- **Evidence view:** Source coverage, conflicts between records and rules for interpreting reported versus observed measures.
- **Architecture explainer:** Shared identifier, registries, interoperability, rules/events and decision views.

## Demonstration geography

Jalandhar and Ludhiana (Punjab); Thane (Maharashtra); Surat (Gujarat); Guwahati (Assam); and Karnal (Haryana).

## Run locally

Open `index.html` in a modern browser. It is a self-contained HTML file with embedded styling, scripts and image assets; no installation or build step is required.

To publish with GitHub Pages, deploy the repository root on the default branch (Settings → Pages → Deploy from a branch → root). The entry point is `index.html`.

## Data and evidence limitations

All observations, identifiers, financial values and contractor names in this prototype are **synthetic**. Geography is schematic, not a surveyed boundary. The prototype is not a source of official government statistics, verified service outcomes or live government records.

Project construction progress is distinguished from verified operational service delivery. The proposed shared-identifier and rule-based coordination model is demonstrated through local prototype logic, **not** a live connection to government registries or APIs.

The prototype's as-of date is controlled by the `ASOF` value inside `index.html` (initially 21 September 2026).

## Repository contents

| File | Purpose |
| --- | --- |
| `index.html` | Standalone prototype |
| `README.md` | Overview, usage and limitations |
| `.gitignore` | Excludes incidental editor and operating-system files |
| `.nojekyll` | Allows direct GitHub Pages publication without Jekyll processing |

## Licence

No open-source licence has been assigned in this repository starter. Confirm the intended ownership and distribution terms before adding a `LICENSE` file.
