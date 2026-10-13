# NeatRelay operations — handover

## Current state

Date: 12 October 2026. Relay Spectrum redesign published and verified; role-based delegation and local workspace behaviour preserved.

Repository: https://github.com/nathanwoork/NeatRelay

Website target: https://nathanwoork.github.io/NeatRelay/

Trello: https://trello.com/b/EkpD9cQ1 — shared execution record, not automatically synchronised.

## Change log

### 6 October 2026 — original dashboard

Published a 24-task / seven-workstream plan inside the portfolio repository's `neatrelay/` folder. Six views, local status/notes, tasks, import/export and backup viewer. Four completed entries represent planning decisions/drafts, not customer traction. Browser checks covered task edits, reload persistence, filtering, backup restoration and mobile layouts.

### 6 October 2026 — dedicated repository and delegation

- Created a distinct public NeatRelay repository so it appears in Nathan's repository list.
- Added a visible Repository link and project-handover link.
- Added Delegate work with seven role templates, task selection, person, acceptance reviewer, date, brief and handoff stage.
- Delegation records are browser-local, included in version-1 JSON backups; older backups without assignments remain supported. Saving does not hire, invite, send messages or grant access.
- Added AGENTS.md instructions requiring this handover to be updated with every project change.
- Preserved task IDs and storage key. The canonical site uses the same nathanwoork.github.io origin, so existing browser-local workspace data remains available at the new path.
- Planned a redirect from the original /neatrelay/ URL after the new site is verified. Portfolio content otherwise stays separate.
- Syntax passed; browser and public deployment checks are in progress.

## Next steps and boundaries

Review the working brand, complete the 60-hour preparation plan and validate the small-studio offer. No employees or clients are implied by role templates. Before collaborative live assignments, choose a shared authenticated system and explicitly agree access; this public static dashboard is a planning companion.

Customer-service prototype: https://github.com/nathanwoork/NeatRelay-Service. Private records, personal contact lists, funding documents and JSON exports must not be committed here.

Every change must append a dated progress entry with tests, unresolved issues and next steps; see AGENTS.md.

### 6 October 2026 — local release checks passed

Dashboard: syntax and meaningful backup validation passed, including legacy imports, assignment round-trip, invalid roles/stages/dates and safe escaping. Browser checks confirmed handoff saving, reload persistence, brief content and backup inclusion; synthetic QA data was reset. Mobile delegation layout has no horizontal overflow at the tested 390px viewport.

Service: desktop and mobile layout/navigation checked; package recommendation and contact package selection passed; email draft points to the confirmed address without sending; fictional acceptance is gated by all four checklist items. Process, People and About views checked; no service console errors observed. No horizontal overflow in tested mobile views.

Both public repositories exist and GitHub Pages is configured for main/root. Publishing and public deployment verification follow this entry. Remaining limitations: static prototypes, local-only delegation, no real client portal or enquiry backend, draft pricing and unvalidated business assumptions.

### 6 October 2026 — published and verified

- Dashboard source: https://github.com/nathanwoork/NeatRelay — application commit 174189f7206ff2cdafe0f839c8d9d1fbc1cb81b7.
- Dashboard site: https://nathanwoork.github.io/NeatRelay/ — live delegation page verified; fresh handoff register contains no QA assignments.
- Service source: https://github.com/nathanwoork/NeatRelay-Service — application commit ac00ae219298fe7c833915ed7f9c3b5dce2c197f.
- Service site: https://nathanwoork.github.io/NeatRelay-Service/ — live home and pricing navigation verified.
- Both application commits have successful GitHub Pages workflow results. Desktop screenshots saved in local focused/verification; mobile checks and interactions are recorded above.
- Portfolio repository commit 81b5d335503a6d1382d3267bcacd63f7ca9a95ea publishes a redirect only at the legacy neatrelay/index.html plus legacy documentation. The root portfolio is preserved. Redirect deployment verification is recorded in the central local log.
- This release also updates the workspace index and handover instructions. Historical entries above describe earlier states; this entry and Current state take precedence.

Next: Nathan reviews the service copy and draft prices, prepares one complete synthetic workflow with failure tests, and validates the offer before accepting client work. Future hires can be planned through Delegate work; actual shared assignments remain in Trello or another agreed system. No invitations, hiring, emails, payments or client-data processing occurred in this release.

### 12 October 2026 — Relay Spectrum redesign in progress

Applied Nathan’s dashboard references and researched Asana/monday examples. Added shared semantic colour tokens, locally hosted licensed Manrope/Space Grotesk fonts, an honest task-completion dial, themed dashboard/service views and a reusable visual design guide. Storage, backup schema, pricing and service boundaries are preserved. Desktop first pass inspected; responsive/interaction verification and publishing follow.

### 12 October 2026 — redesign verification complete; publishing

Relay Spectrum now covers both sites, including boards, forms, delegation, pricing, profile/vision and the client demo. The canonical shared kit is in focused/design-system; each repository includes DESIGN-LANGUAGE.md, design-system.html, colour tokens, embedded fonts and OFL notices. Local playbook, brand memo and workspace index now point to this direction.

Verification: desktop (approximately 1280px), tablet (820px), phone (390px) and narrow phone (320px) were rendered. All dashboard/service routes were checked for phone overflow; dashboard secondary routes also checked at desktop. Tablet sidebar overlap was found and fixed by aligning CSS and JavaScript drawer breakpoints at 900px; menu navigation, Enter and Escape were rechecked. Task filtering, edit dialog, count recalculation (4/24 to 5/24), reload persistence and restoration to the original task status passed. Legacy backup/delegation tests passed. Service package selection, email draft preparation without sending, demo workboard and four-check acceptance gate passed. The design specimen status/density controls passed. No JavaScript errors appeared in inspected tabs.

Selected text colour pairs meet 4.5:1 (6.0–13.8:1 in checked semantic pairs). Shared files are byte-identical across the two sites. No full accessibility certification or cross-browser/device-lab testing is claimed. Fonts cover the current Latin content; non-Latin localisations require a deliberate font extension. The dashboard is still browser-local with no automatic Trello sync; service remains a prototype. No new customer, hiring or financial outcomes are implied.

Next: publish and verify GitHub Pages, then Nathan can review the visual direction. Continue business validation and implementation tasks separately.

### 12 October 2026 — Relay Spectrum published

Both GitHub Pages application deployments succeeded and the live dashboard and service home were inspected. Dashboard redesign commit: 2eb62a96ccefb05fa19a971e6da03d9477b7982e. Service redesign commit: 0f4102ef676f5f8de9ef41c9981a5e1b619c7d78.

Live sites: https://nathanwoork.github.io/NeatRelay/ and https://nathanwoork.github.io/NeatRelay-Service/. Reusable visual guide: https://nathanwoork.github.io/NeatRelay/design-system.html (also included in the service repository). Canonical workspace sources: focused/design-system/. Screenshot evidence and QA details are in focused/verification/2026-10-12/.

This entry supersedes earlier visual descriptions. Task data and dates still describe the original planning snapshot; a visual release is not a task completion or business launch. Nathan can now review this direction and use the guide for future projects.

### 13 October 2026 — clarified first-sale service

Nathan selected observation-led workflow improvement with a Google Sheets dashboard and process documentation for one agreed flow. Updated the pilot description, deliverables, exclusions and quote basis; RM1800 is no longer the generic public pilot price. Added an illustrative handover explanation, KL/Selangor observation and optional separately scoped web dashboards. Dashboard planning decisions reflect the current first-sale priority; existing task statuses are preserved.

Private intake, scope/pricing, draft terms and delivery instructions were prepared in the Astra Sandbox project. A fictional Google Sheets starter was created and checked for formula updates, typed dropdown tables and visual layout. Internal documents, spreadsheet links, pricing calculations, buyer details and account identifiers are not published here. Client-specific approval and delivery remain future work. Website syntax and responsive/interaction checks are being completed before release.

### 13 October 2026 — verification and release preparation

Native Google Sheets starter was visually reviewed on all four tabs; formula changes and restoration passed after repairing imported dates. Public service copy explains one observed process, a Sheets dashboard, operating documents, guided implementation and scope-dependent price. The public repositories exclude all private starter links, terms drafts and quote calculations. Service page desktop/mobile and package enquiry checks completed before publishing. The working brand is retained and no sale/client outcome is recorded.

### 13 October 2026 — first-sale offer published

Dashboard planning update commit: 4b340ff6ec59b1cea941d0f7213daa54a3413bb8. Service clarification commit: 4405dc7770885c3ec3e128d92fd29fdb9479ce39. Both GitHub Pages deployments succeeded; live service pricing shows Scoped quote and the current dashboard records the new first-sale direction. Desktop/mobile service checks passed, and the pilot enquiry button selects One-Flow Pilot. Native starter recalculation and new-record tests passed; sample data restored. Private working documents and workbook are kept out of the public repositories. No sale, event attendance, outreach, signed contract or operational client outcome is claimed.
