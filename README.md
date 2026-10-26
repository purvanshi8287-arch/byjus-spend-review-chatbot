# BYJU'S Spend Review — evidence chatbot prototype

A local, source-grounded assistant for reviewing significant marketing, sponsorship and expansion proposals. The chat answers from a dated public evidence pack, cites sources, labels limitations, identifies missing proposal inputs, and keeps final decisions with authorised human reviewers.

## Run it

Open `index.html` in a current browser. No installation, server, API key or account is needed. The chatbot is deterministic and works offline. Citation links open the underlying public sources when clicked.

For a structured form-based review, open `proposal-review.html`. The original form includes the 12 Session 7 stress-test scenarios. The full public source register is `web-evidence-pack.md`.

## What the chatbot covers

- Historical FY22 consolidated and standalone/core-business reported figures, kept separate by scope.
- Historical advertising expenditure, FIFA and BCCI sponsorship records, Aakash/Epic announcements, CIRP portal status, sector context, DIKSHA, CCPA, a limited external survey, FEMA reporting and DPDP legal sources.
- Source citations, evidence-quality caveats, current-status dates, limits of public evidence, proposal-level missing-input checks, and human-review boundaries.
- A lightweight input safeguard for common personal identifiers and credentials.

The chatbot does not connect to an AI service or a live retrieval system. It does not write chat messages to local storage or transmit them to a server. Messages stay in the open tab’s memory and disappear when it is refreshed or closed. Do not enter confidential or personal data; use authorised internal systems for restricted evidence.

## Evidence and limits

The public source register was checked to 26 October 2026. Its W01–W15 references are not mapped to the project's original E01–E08 Evidence Register because that register was not supplied. Public reporting can support historical context, but it cannot establish a proposed spend's incremental revenue, ROI, customer demand, current budget, approval threshold or causal effect. Financial figures have distinct consolidated and standalone scopes. Historical ad spend is neither campaign ROI nor an industry benchmark. Public sources remain candidate evidence until project and finance reviewers approve them.

The evidence pack identifies which proposal inputs must come from authorised internal sources. Use aggregate, de-identified extracts only. An assistant response is advisory: finance and business leadership retain authority to approve, reject, negotiate or commit funds. Legal and privacy issues require qualified review of the particular proposal and the rules in force at decision time.

## Files

- `index.html`, `chatbot.css`, `chatbot.js` — the evidence chat interface and deterministic local response logic.
- `proposal-review.html`, `styles.css`, `app.js` — the original proposal review form, including the 12 stress tests.
- `web-evidence-pack.md` — public source register, limitations and proposal evidence checklist.

## Publish as a GitHub repository or live page

This is a static site and is ready for GitHub Pages. In the repository, keep `index.html`, `chatbot.css`, and `chatbot.js` at the root. After pushing the `main` branch, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. GitHub will show the live page address in that section; it follows the form `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`. The repository address follows `https://github.com/YOUR-USERNAME/REPOSITORY-NAME`.

