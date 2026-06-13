# Sonder — Future Ideas

A parking lot for concepts we've prototyped but aren't shipping yet.

---

## The Sonder Assessment (parked — not live)

**Status:** Built as a working prototype, intentionally NOT linked from the live site (per founder decision, not ready to launch).
**File:** `future/Sonder Assessment (future concept).html`

### The idea
A 10-minute self-diagnostic that scores a visitor's organization across the real
**10 Pillars of Organizational Alignment** and turns the result into a lead.

### What the prototype already does
- Intro screen (what it is, ~10 min, what you get) with resume/start-over.
- 10 pillar screens, 2 plain-language statements each, rated on a 4-point agree/disagree scale.
- Progress bar + back/next; answers persist in the browser (localStorage).
- Lead-capture step (name, work email, company, role) before results.
- Results screen: animated **Sonder Health Score** (0–100), a pillar-by-pillar bar
  breakdown (low pillars flagged), and a "Where to Focus First" panel naming the
  three lowest pillars with a recommended first move each.
- Ends on a "Book a Discovery Call" CTA. Retake option.

### What it still needs before going live
1. **Real lead capture.** Right now the form is front-end only — it shows a
   "report on its way" confirmation but does not email or store anything.
   Needs wiring to a form service / CRM / email (e.g. send results + notify Sonder).
2. **Emailed report.** Generate and send the actual pillar-by-pillar PDF/email.
3. **Founder review of scoring.** Tier thresholds (Strong / Developing / Under Strain /
   At a Turning Point) and the per-pillar "focus first" recommendations are drafts.
4. **Confirm the questions** map to how Sonder actually wants to diagnose each pillar.

### How to revive it later
- Move the file back into `site/` and re-link the hero, nav, and contact CTAs
  (search the site for "Book a Discovery Call" — the assessment links used to sit
  alongside those).
