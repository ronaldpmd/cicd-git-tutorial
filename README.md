# CICD Git Tutorial (Dataform Project)

This project uses Dataform to manage BigQuery transformations with a local VS Code development workflow.

## Setup
1. **Python Environment:**
   - `python -m venv .venv`
   - Activate and run `pip install -r requirements.txt`
2. **Dataform CLI:**
   - Run `npm install` to set up Dataform dependencies.

## Quality Control
- **Linter:** We use `SQLFluff` for SQLX formatting.
- **CI/CD:** GitHub Actions (SuperLinter) runs on every push to ensure code quality.