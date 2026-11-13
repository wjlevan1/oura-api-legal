# Personal Oura ETL — Legal Notices

Public-facing legal notices for a personal, noncommercial Oura API V2 integration operated by [@wjlevan1](https://github.com/wjlevan1). This repository is separate from any private ETL implementation and contains **no health data, OAuth tokens, or credentials**.

## Legal documents

- [Privacy Policy](docs/privacy.md)
- [Terms of Service](docs/terms.md)

These GitHub file links are publicly readable now. They can be supplied as public policy URLs for the Oura developer application.

## Public GitHub Pages site

The `docs/` folder is configured as a Jekyll-compatible site with an index page and friendly policy URLs:

- [Legal notices](https://oura.levanlabs.com/)
- [Privacy Policy](https://oura.levanlabs.com/privacy/)
- [Terms of Service](https://oura.levanlabs.com/terms/)

GitHub Pages is configured to deploy from the `main` branch's `/docs` folder. The custom domain is set in `docs/CNAME`, with DNS managed separately. HTTPS is available after GitHub finishes certificate provisioning.

## Scope and changes

The documents describe the intended personal-use integration. The operator should keep them accurate if the application's collection, retention, storage, disclosure, or audience changes. In particular, Oura API data handling must comply with the [Oura API and MCP Agreement](https://cloud.ouraring.com/legal/api-agreement), including its restrictions on AI-model use and data retention.

For privacy-related inquiries, use the contact information associated with the Oura application registration; do not post sensitive personal or health information in public repository issues.
