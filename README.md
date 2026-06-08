# Mileage Tracker v3

Single-user web application for IRS substantiation-grade mileage logging with polished UI, dark mode, and mobile-responsive layout.

## Features

- Single-user authentication (Argon2id, session expiry, rate limiting)
- Vehicle management with per-tax-year odometer readings
- Trip management with §274(d) substantiation fields
- Time-effective IRS mileage rates (seeded reference data)
- Deduction calculation and year-end summary
- IRS-compliant CSV and PDF export
- Design system with light/dark themes and responsive layout (360px–desktop)

## Quick start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python run.py
```

Open http://127.0.0.1:8000 and register the single user account.

## Tests

```bash
python -m unittest discover -s tests -v
```
