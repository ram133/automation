# Automation

**Reusable GitHub Actions, scripts, and self-running systems.**

Patterns used across the Ray product ecosystem (NEWS, digital products, agents, and more).

Goal: keep products alive with zero or near-zero manual work.

---

## Available Patterns

| Workflow | Purpose | Trigger |
|----------|---------|---------|
| `example-daily.yml` | Base daily task template (6 AM ChST) | schedule + manual |
| `update-timestamp.yml` | Writes a LAST_UPDATED.txt daily | schedule + manual |
| `link-checker.yml` | Checks Markdown links, can open issue | weekly |
| `stale-issues.yml` | Marks and closes inactive issues/PRs | daily |
| `auto-label.yml` | Auto-labels issues & PRs from keywords | on open/edit |
| `star-notifier.yml` | Creates an issue when someone stars the repo | on star |
| `hello-on-issue.yml` | Posts a welcome comment on new issues | on issue open |

Copy any of these into your own repos under `.github/workflows/` and customize.

---

## How to use

1. Copy the desired `.yml` file into your target repository’s `.github/workflows/` folder
2. Adjust the cron schedule or conditions as needed
3. Commit and push — the Action becomes active immediately

For product repos, start with `example-daily.yml` or `update-timestamp.yml` and expand from there.

---

## Live Examples

- `services` repo now runs the daily timestamp workflow
- `product-kit` ships with a daily maintenance stub
- `NEWS` runs a full daily content generation pipeline

---

## Contact & Support

| Method | Details |
|--------|---------|
| **Phone / Signal** | +1 (671) 685-9138 · +1 (671) 456-6963 |
| **Email** | 3659745@gmail.com · crh2123@icloud.com |
| **Website** | [ray.services](https://ray.services) |
| **PayPal** | crh2123@icloud.com |
| **Custom automation** | $1/min live sessions |

All payments go directly to Ray.

---

## Related

- [services](https://github.com/ram133/services) — Live AI automation & consulting
- [product-kit](https://github.com/ram133/product-kit) — Starter kit that already includes a daily workflow
- [NEWS](https://github.com/ram133/NEWS) — Daily automated AI newsletter (production example)
- [digital_factory](https://github.com/ram133/digital_factory) — Ship products on repeat

**Built in public with Grok.**
