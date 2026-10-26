# Multi-Tenant SaaS Backend

Employee-management API where many companies (tenants) share one database
without seeing each other's data.

**Stack:** FastAPI · PostgreSQL · SQLAlchemy 2.0 · Alembic · Docker · AWS

## Status

Work in progress, following a 9-week build plan.

## Local setup

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements-dev.txt
pre-commit install
```
