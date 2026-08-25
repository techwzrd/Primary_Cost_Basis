# Primary_Cost_Basis

Tracking the adjusted cost basis of a Florida primary residence, so that the eventual
taxable gain at sale is computed from documented evidence rather than reconstructed
from memory.

## Contents

| File | What it is |
| --- | --- |
| [`cost-basis-plan.html`](cost-basis-plan.html) | The plan. Open it in any browser &mdash; no server, no dependencies, works offline from the filesystem. |

## Using the plan document

The file has two tabs.

**The Plan** covers why cost basis matters at sale, which costs the IRS allows you to add
and which you must subtract, Florida-specific considerations (hurricane hardening,
mitigation grants, storm casualty and insurance pairing, documentary stamp taxes, county
permit records), a build-versus-spreadsheet comparison, the architecture and ledger
schema, how to harvest existing receipts from email and cloud and local storage, the
ongoing capture workflow, reporting, retention, a phased roadmap, and risks.

**Open Questions** is a 36-question form covering the decisions that have to be settled
before anything gets built. Answers save automatically to your browser's local storage
and never leave your machine. Use **Export Markdown** or **Export JSON** to produce a
copy you can send back.

Because answers live in browser local storage keyed to the file's location, opening the
file from a different path or a different browser shows an empty form. Export once you
have finished a pass.

## Basis of the tax guidance

Structured around IRS Publication 523 Worksheet 2, so the ledger schema maps directly
onto the lines that must eventually be filled in:

- [Publication 523, Selling Your Home](https://www.irs.gov/publications/p523)
- [Publication 551, Basis of Assets](https://www.irs.gov/publications/p551)
- [Publication 530, Tax Information for Homeowners](https://www.irs.gov/publications/p530)

This is a record-keeping plan, not tax advice. Confirm classification decisions with a
qualified CPA.
