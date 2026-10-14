<!-- lokstack:start -->
## Local environment (kept up to date by Lokstack)

- **Start**: not set yet. Ask the user to choose a start command in Lokstack (Run & logs) instead of guessing one.
- **MySQL**: 127.0.0.1:3308, database `test_project` (from `DATABASE_URL` in `.env`)
- **MySQL**: 127.0.0.1:3307, database `test_project` (from `DATABASE_URL3` in `.env`)
- **PostgreSQL**: 127.0.0.1:5434, database `test_project` (from `DATABASE_URL2` in `.env`)
- **Logs and errors**: Lokstack → this project → Run & logs, or the MCP tool `project_logs`.
- **Secrets**: never print, copy or commit values from `.env`. Add new settings to `.env.example` with an empty value.
<!-- lokstack:end -->
