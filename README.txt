Townlight HR v0.1.1

Townlight HR supports HR policy work without becoming an HRIS. It ships personnel-policy lookup outlines, handbook summaries, job-description drafts, optional database-backed job/onboarding workpapers, classification references, onboarding and training checklists, intake templates, source review, sensitive-topic preflight, FastAPI endpoints, tests, docs, and browser QA evidence.

It does not ship payroll, benefits administration, personnel records management, employment-law advice, autonomous HR decisions, grievance case tracking, personnel-file ingestion, live LLM calls, or external HR/payroll connector runtime.

Run locally:
  python -m pip install -e ".[dev]"
  python -m uvicorn civichr.main:app --host 127.0.0.1 --port 8138

Set CIVICHR_WORKPAPER_DB_URL to persist job-description drafts and onboarding packets. Without it, Townlight HR remains deterministic and stateless.

License: Code: AGPL-3.0-only, with the TownLight Public Institution Exception for qualifying deployments. See LICENSE and LICENSE-EXCEPTION.md. Documentation: CC BY 4.0 (LICENSE-DOCS).
