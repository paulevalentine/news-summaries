# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

A git-tracked archive of daily news summaries stored as Markdown files. There are no build, test, or lint commands — this is a plain-text content repository.

Remote: `https://github.com/paulevalentine/news-summaries`

## File naming and location

All summaries live in `summaries/` and are named `YYYY-MM-DD.md` (e.g. `summaries/2026-04-14.md`).

## Document structure

Each summary follows this structure:

```markdown
# Daily News Summary: YYYY-MM-DD

---

## Section 1: World News — Top Stories

### 1. Story Headline

Body paragraph(s).

[Read more: Source Name](url) | [Source Name](url)

---

### 2. Story Headline
...

---

## Section 2: UK News — Domestic Overview

### 1. Story Headline
...

---

*Sources footer.*
```

Key conventions:
- Each story ends with `---` (horizontal rule)
- Source links use the format `[Read more: Label](url) | [Label](url)` inline at the end of each story
- The final line is an italicised sources note listing all outlets used
- UK-specific stories use `[Read more: Label](url)` style rather than the `**Sources:**` bold variant seen in older files
- World news section is always Section 1; UK news is always Section 2
- Stories are numbered sequentially within each section (no fixed count)
