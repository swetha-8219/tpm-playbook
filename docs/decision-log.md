# Decision Log (ADR-style)

Log decisions here so they never have to be re-argued. One entry per decision, kept short.

## Template

### ADR-[number]: [Decision title]
- **Date:** [Date]
- **Decided by:** [Name(s)]
- **Status:** Accepted / Superseded by ADR-[number]
- **Context:** [What problem were we solving? Keep it to 2–3 sentences.]
- **Decision:** [What we decided, plainly.]
- **Alternatives considered:** [What else we weighed, and why not.]
- **Consequences:** [What this commits us to, good and bad.]

---

## Example

### ADR-001: Use a single RAID log per program
- **Date:** 2026-10-25
- **Decided by:** Program team
- **Status:** Accepted
- **Context:** Risks were tracked in three different docs, so nobody had the full picture in reviews.
- **Decision:** One RAID log per program, reviewed weekly, owned by the program manager.
- **Alternatives considered:** Separate risk and dependency docs (rejected — they drift apart); tracking in chat (rejected — not searchable).
- **Consequences:** One source of truth, but the log needs a weekly owner or it goes stale.
