# Dogs Mobile Grooming — Listing Presentation Mockup

An interactive product/UX concept for improving Dogs Mobile Grooming groomer-detail pages.

## Live demo

**https://tamyres-local.github.io/dog-listing-presentation-mockup/**

## Concepts included

The prototype now presents **four listing-page directions**:

1. **Evidence-led Decision Hybrid** — the research-informed recommendation. It combines a Trust-first evidence spine, Comparison-first decision summary, and Booking-first provider handoff.
2. **Trust-first marketplace** — evidence and freshness appear near the claim while contact actions remain prominent.
3. **Booking-first concierge** — prioritizes fast calls and website visits, especially on mobile.
4. **Comparison-first directory** — leads with structured attributes and explicit `Not confirmed` states.

The interactive demo supports:

- Desktop and mobile presentation modes
- Field-level correction flow
- Business-claim flow
- Evidence-ledger modal
- Verified, source-backed, unknown, stale, and suppressed states

## Recommended production direction

Use the **Evidence-led Decision Hybrid** as the production direction. It deliberately combines:

- The provenance, freshness, and correction model from Trust-first
- The explicit unknown-state cards and normalized facts from Comparison-first
- The persistent mobile provider handoff from Booking-first

This recommendation follows a public-page review of the ranking gatekeepers and scalable service competitors identified in the August 2026 DOG search study. City/category pages should own generic local discovery; groomer-detail pages should help users evaluate one provider without presenting unverified prices, availability, credentials, or services as facts.

## Integrity rules represented by the mockup

- Evidence status belongs to individual fields, not merely the listing as a whole.
- `Unknown` is distinct from verified `No`.
- Public-source data is narrower than owner-confirmed data.
- A successful HTTP response does not prove an external destination is the correct business profile.
- Invalid or unverifiable destinations are suppressed rather than guessed.
- Claim submission does not grant verification immediately.
- Claiming does not buy placement, change rankings, or certify service quality.
- Booking, pricing, availability, licensing, and insurance are never implied without reliable support.

## Important note

This repository contains a **design concept**, not production code. Names and selected business details are adapted from a representative live listing. Dates, evidence states, and verification labels are illustrative product states—not production verification records.

## Local use

Open `index.html` directly in a browser. The mockup has no build step or runtime dependencies.
