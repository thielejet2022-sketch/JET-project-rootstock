# Tools & systems (the Rootstock stack)

| Tool | Role | Notes |
|------|------|-------|
| Airtable | System of record | Base: [Rootstock](https://airtable.com/appwFte1VIabLCu5A). Tables: Beds, Varieties, Seed Lots, Plantings, Harvests, Suppliers, Expenses. |
| Notion | Journal & notes | Photo journal, lessons learned, per-step notes |
| Make | Automation | Candidate for iPhone photo → journal workflow, Airtable ↔ Calendar sync |
| Google Calendar | Dedicated gardening calendar | Order seeds, start seeds indoors, direct sow, transplant, harvest dates |
| Google Sheets | Secondary/lightweight tracking | Backup for cost tracking if Airtable isn't the fit |
| Google Slides | Not yet scoped | JET listed this as available; use TBD |
| Google Drive | Photo storage | Landing zone for iPhone photos before/instead of Notion embed |
| GitHub (rootstock repo) | Memory system home | Version-controlled CLAUDE.md + memory/ — JET wants a structured, versioned system |

## Airtable schema (built Jul 2026)
| Table | Purpose |
|-------|---------|
| Beds | The 5 growing areas (Bed 1, Bed 2, Pumpkin Patch, Sunflower Patch, Expansion Area) |
| Varieties | Master catalog of every plant/variety, idea or active |
| Seed Lots | Purchased packets and saved seed, linked to Variety + Supplier |
| Plantings | The season instance — Variety + Bed + calendar dates (order/start/direct sow/transplant/harvest) + status |
| Harvests | What came off a Planting — quantity, unit, destination (eaten/canned/seed saved/given away) |
| Suppliers | Jim's Worm Farm, Jake (tree service), future seed companies |
| Expenses | All spend — seeds, tools, infrastructure, irrigation, deer control — optionally linked to a Planting |

Seeded with the current Summer 2026 plantings (Bed 1, Bed 2, pumpkin patch, sunflower patch) and known suppliers. Calendar date fields on Plantings are currently empty — fill in as seed-order/start/sow dates are decided, since Google Calendar will eventually sync off these.

## Not yet decided
- Exact photo capture workflow (iPhone → ? → Notion/Drive/Airtable)
- Whether Google Sheets duplicates or replaces any Airtable function
- Google Slides' role in the project
