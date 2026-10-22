# ShipDesk release readiness

- Author: Sriman
- Candidate: 1.1.0
- Local image ID (not merely image tag): sha256:e00345b13d90356457a410e76d862d2bc23d0e85cdbc6fec0faa6b42730cb4d7
- Local /health and /config result: PASS, health status ok; ShipDesk production version 1.1.0
- Scope: LOCAL VALIDATION ONLY; approval NOT REQUESTED; NOT DEPLOYED to production.
- Hypothetical incident decision and two supplied signals: Propose rollback to known-good 1.0.0; failures rose to 30% and most readiness checks failed. Previous version is confirmed healthy and schema-compatible. Hypothetical only, not executed.
- Proposed post-recovery checks: confirm intended version, ready instances, health/config endpoints, and request failure rate restored near 0.2% baseline. No recovery result claimed.

Final commit, annotated tag identity, successful Actions URL and matching
hosted commit go in submitted PDF AFTER this file is committed. Do not edit
this file to insert its own commit hash, avoiding a circular commit identity.
