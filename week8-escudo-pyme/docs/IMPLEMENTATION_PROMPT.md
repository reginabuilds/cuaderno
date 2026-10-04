# Implementation Prompt — ESCUDO PyME

Build exactly the MVP in `docs/PACKET.md`.

1. Shell: Home, Mi Escudo, Incidentes, Coordinador. Acceptance: navigation works and mobile layout is usable.
2. Prioritized shield: five synthetic controls, priority, status and plain-Spanish explanation. Acceptance: first action is obvious and recommendation is distinct from verified/completed.
3. Simulated AI: label every AI output `IA · simulada`. Acceptance: it explains/prioritizes but never certifies safety or changes state autonomously.
4. Incident response: five ordered steps — confirm/contain, preserve evidence, identify affected data, communication, closure. Acceptance: next owner and human escalation are visible; no attacker contact/ransom action exists.
5. Coordinator: show incident ID, owner, IT provider, severity, next action, deadline and closure note. Acceptance: capacity is explicit and triage is visible.
6. Security floor: no secrets, no personal data, no sensitive uploads, no persistent personal-data store.
7. Test/fix/redeploy: mechanical pass + synthetic persona pass; document one confusion and fix it before final demo.

Suggested commits:
- feat: add escudo pyme shell
- feat: add prioritized shield workflow
- feat: add simulated incident response
- feat: add coordinator triage view
- test: fix persona comprehension issue and finalize demo

Demo path: Home → Mi Escudo → MFA → simulated AI recommendation → Incidentes → response steps → Coordinador → human escalation/capacity.