# hubspot-pipeline-hygiene-ledger

Board-readable Kinetic Gain proof repo for **HubSpot** signal coverage.

## Signal lane

- Vendor / platform: HubSpot
- Domain: CRM / RevOps
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

Pipeline hygiene, automation sprawl, lifecycle stage drift, and lead routing evidence.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for HubSpot without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.
