---
name: advisor-outreach
description: Find, rank, and contact prospective graduate advisors in China from the user's research direction, CV, transcript, advisor profiles, and outreach template. Use when the user wants to screen 985/211/Double First Class faculty by research fit, divide advisors into A/B/C tiers, extract personal strengths from materials, or batch-generate personalized Chinese or English advisor outreach emails for 保研, 考研, 直博, master's, PhD, or RA applications.
---

# Advisor Outreach

## Core Principle

Prioritize research fit over school prestige. Use 985/211/Double First Class status, discipline strength, and geography only after advisor-topic alignment and evidence quality are assessed.

Produce outreach that sounds deliberately written for the specific advisor. Avoid generic compliments, over-formal bureaucratic wording, inflated claims, and repeated template phrasing.

## Workflow

1. Gather inputs:
   - User CV/resume, transcript, and optional personal statement.
   - User's outreach template or preferred tone.
   - Target advisor list, or a request to search for advisors.
   - User's research direction, degree target, school constraints, and geographic preferences.
2. Extract the user's reusable profile:
   - Education, GPA, rank, core courses, English scores, awards, competitions.
   - Research topics, methods, papers, patents, project responsibilities, tools, and evidence of independence.
   - A concise "advantage bank" that can be selectively reused per advisor.
   - For extraction details, read `references/material-extraction.md`.
3. Build or evaluate advisor profiles:
   - Advisor name, school, school type, school/discipline strength, lab or group, recent papers, projects, admissions hints, and reliable links.
   - For source and evidence rules, read `references/advisor-profile.md`.
4. Tier advisors:
   - A: highly aligned, active, and worth first contact.
   - B: broadly aligned and suitable as a main backup.
   - C: weakly aligned, exploratory, or strategic backup.
   - For scoring and ranking rules, read `references/matching-rubric.md`.
5. Generate outputs:
   - Advisor ranking table with evidence links and recommended contact priority.
   - One personalized email per advisor, not a mass-mail variant with only names swapped.
   - Optional subject lines, follow-up emails, and tracking table.
   - For format, read `references/output-schema.md`.

## Email Generation Rules

Use the user's template as a style reference, not as fixed text. Preserve accurate facts from the user's materials, but rewrite the email around the advisor's actual work.

Each email should include:

1. Subject line with year, purpose, name, school, and concise identity.
2. Opening that is polite but not stiff.
3. A compact self-introduction using only the strongest relevant facts.
4. A research-experience paragraph that emphasizes concrete work done by the user.
5. A specific advisor-fit paragraph grounded in the advisor's papers, lab direction, or projects.
6. A forward-looking paragraph explaining what the user wants to continue learning in that group.
7. A concise close asking whether there is an opportunity to communicate further.

Do not claim the user read a paper, understands a project deeply, or has a strong preference for an advisor unless the source evidence supports it. If evidence is weak, use careful wording such as "我注意到您团队近年来关注..." rather than "我认真研读了...".

For reusable sentence patterns and anti-template guidance, read `references/email-style.md`.

## Batch Mode

When the user provides multiple advisors, create one table plus individual email drafts. Keep shared achievements consistent, but vary:

- The research-fit paragraph.
- Which user experiences are emphasized.
- The proposed future direction.
- The subject line if the advisor's field differs.

Flag missing advisor evidence instead of inventing specifics. If only names and schools are provided, first ask for permission to search or request advisor homepage/paper links.

