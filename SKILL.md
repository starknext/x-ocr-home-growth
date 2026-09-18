---
name: X OCR Home Growth
description: Use when growing X Original Content Rewards verified Home Timeline impressions toward 500k, writing OCR progress posts, or running curated Agent/Cursor niche originals instead of reply-farming.
---

# X OCR Home Growth

Playbook for pushing **verified Home Timeline impressions** for X Original Content Rewards (OCR), not raw Analytics views.

## Goals and metrics

Track three different numbers:

| Metric | What it is | Counts for OCR 500k? |
|--------|------------|----------------------|
| Analytics impressions | Broad views | No (proxy only) |
| Verified Home Timeline impressions | Premium users seeing the post on Home, ≥50% on screen | **Yes** |
| Reply impressions | Views on replies | **No — excluded** |

Official: https://help.x.com/en/using-x/original-content-rewards

Eligibility reminders: Premium tier, 500+ verified followers, 18+, good standing, and **500,000 verified HT impressions in 90 days**. Replies do not count. Ads / fake / duplicate impressions do not count.

## Stop doing

- Reply farming / spray quoting for "volume"
- News-wire quote spam
- Empty agree / engagement bait / empty mutual-follow scripts
- Aggregating or lightly editing others' content and calling it original
- Dozens of posts/day (author-diversity decay)

## Do instead (priority order)

1. **Lead with conclusion / conflict / number** in line 1; evidence next (screenshot, chart, short demo).
2. **Stay in one niche** long enough for retrieval to learn you (e.g. Agent / Cursor / local-private LLM / computer use / enterprise ops).
3. Prefer **experiment → data → reusable workflow** over slogans.
4. Publish **OCR progress posts**: baseline → today delta / strategy → next experiment.
5. Use replies only to pull attention back to originals — never as the OCR plan.
6. Cadence: roughly **1 hard original/day**, optional 0–1 high-signal reply; weekly 1–2 deeper experiment posts.

## Content formulas

### A. OCR progress

```
[number or blunt claim]
baseline: X / 500,000 verified HT
what changed today / strategy
next experiment
```

### B. Pain → fix → reusable rule

Concrete ops story (gateway, local LLM failure paths, agent audit trail, retry/idempotency).

### C. Screenshot story

Real UI/log screenshot + surprising event + your judgment.

### D. Benchmark / ship note

One-line capability + proof media + who should care.

## Daily operator checklist

1. Confirm logged into the target account.
2. Read Rewards page (verified HT progress) and yesterday's top original views.
3. Ship **one** required original (formulas A–D).
4. Optionally one reply under a *rising* niche post — conflict or firsthand only.
5. Evening: record Analytics day total + Rewards HT number; note which original moved.

## Algorithm notes (public code, approximate)

- For You mixes in-network + out-of-network retrieval; ranking uses predicted actions (copy-link / reply / quote / follow weigh more than like).
- Author diversity dampens spraying many posts in a short window.
- Originals are the main discovery path into non-follower Home; OON replies/reposts are filtered or discounted.
- Sources: https://github.com/xai-org/x-algorithm

## Announcing this skill on X

Problem (OCR vs vanity views) → one concrete result → repo link → invite forks/PRs. Keep the thread dense and screen-fillable.
