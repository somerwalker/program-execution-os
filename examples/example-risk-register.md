# Example Risk Register

This example illustrates how program risks can be documented and tracked during execution.

A risk register provides visibility into potential issues that could affect delivery. It helps program leadership monitor uncertainties, assign ownership, and ensure mitigation actions are underway before risks become delivery blockers.

---

## Example Risk Register

| Risk ID | Date Identified | Target Resolution Date | Last Reviewed | Risk Description | Impact | Likelihood | Risk Owner | Mitigation Strategy | Status | Escalation |
|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | 2026-01-12 | 2026-02-15 | 2026-01-18 | Cloud infrastructure capacity may be insufficient to support peak migration workloads | Migration delays and potential service disruptions | Medium | Infrastructure Lead | Conduct capacity testing and pre-provision additional resources | Monitoring | No |
| R-002 | 2026-01-15 | 2026-02-10 | 2026-01-20 | Security approval process may delay deployment of new cloud environments | Delayed migration schedule | Medium | Security Engineering Lead | Engage security team early and align on required controls | Monitoring | No |
| R-003 | 2026-01-18 | 2026-02-05 | 2026-01-25 | Key engineering resources may be reassigned to competing initiatives | Reduced delivery velocity | High | Program Lead | Confirm staffing commitments with engineering leadership | Active Mitigation | Possible |
| R-004 | 2026-01-20 | 2026-03-01 | 2026-01-27 | Legacy system dependencies may require additional integration work | Extended migration timeline | Medium | Platform Engineering Lead | Conduct early system assessments and define integration plans | Monitoring | No |

---

## How This Register Is Used

Risk registers referenced in `docs/04-risk-management.md` are typically reviewed during regular program cadence meetings to ensure risks remain visible and mitigation actions are progressing.

Program leaders may escalate risks through governance structures when:

- mitigation efforts are not reducing risk exposure  
- delivery milestones may be affected  
- cross-team coordination or executive decisions are required  

Escalation paths and governance structures are described in:

`docs/02-governance-model.md`

---

Part of the Transformation Operating Framework  
https://github.com/somerwalker/transformation-operating-framework

Copyright © 2026 Somer Walker

This material is provided for educational and professional reference.  
Commercial use or derivative consulting frameworks requires permission from the author.
