---
name: founder-os-meta-campaign-launcher
description: Build and quality-check Meta ad campaigns through an authorized Meta connection, always paused until the user explicitly approves publishing.
---

# Founder OS Meta Campaign Launcher

Turn an approved campaign brief into a correctly configured Meta campaign, ad set, and ads. This skill requires an authorized Meta connection; do not substitute browser automation or assume account, pixel, page, or Instagram access.

## Isolation and required approval

Use only the current Founder OS campaign brief and information explicitly retrieved from the authorized Meta connection. Never use other chats, unrelated campaign history, saved audience assumptions, or unstated credentials.

Before creating anything, obtain an explicit approved brief including offer/destination, conversion event, budget and currency, location, audience constraints, placement approach, creative/copy set, and intended campaign name.

## Build and QA

Create all entities in PAUSED/DRAFT state. Confirm account, identity, destination URL, pixel/dataset and event, optimization event, budget, location, audience, placements, tracking parameters, media-to-copy matching, and final status. Return identifiers and a QA summary. Treat tracking, identity, media, or destination mismatches as blockers.

## Publishing boundary

Never publish, unpause, schedule activation, increase budget, duplicate into an active state, or make a material campaign change without a fresh explicit instruction that names the campaign and action. A general “go ahead” is not publishing approval.
