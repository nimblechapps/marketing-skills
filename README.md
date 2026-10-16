# Nimblechapps Marketing Skills

A trimmed, reviewed copy of 15 skills from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT licence, original copyright Corey Haines).

**Pinned upstream version:** commit `365b412152b9542499ca1439426f7fc3cc92bb65` (15 Oct 2026, plugin v2.11.37).

## Skills

| Group | Skills |
|---|---|
| Content and brand | social, content-strategy, copywriting, copy-editing, video, marketing-psychology |
| Events and press | events, influencer-marketing, public-relations |
| Website and search | ai-seo, schema, site-architecture, programmatic-seo |
| Outreach | cold-email, prospecting |

## Changes from upstream

- Only these 15 of 50 skills; eval files removed.
- Trigger descriptions rewritten to sit cleanly alongside Anthropic's Marketing plugin.
- Partner promotions removed (Ploy sections, TGScope-contributed Telegram reference and benchmarks); HeyGen no longer marked "recommended".
- Links into the upstream repo's tools registry converted to plain text, so nothing loads remote content from the upstream repo.
- Reference to the upstream `github-prospects.js` CLI replaced (CLI not bundled).
- Cross-references to skills not included mapped to the Marketing plugin's equivalents where one exists.
- An install-notes block added to every SKILL.md: statistics treated as unverified, project docs used as business context, missing tools skipped, nothing posted or sent without approval.

## Install

In Claude Code:

```
/plugin marketplace add nimblechapps/marketing-skills
/plugin install nimblechapps-marketing@nimblechapps-marketing
```

Or download this repo as a ZIP, rename it to `nimblechapps-marketing.plugin`, and open it in Claude.

## Updates

A weekly check compares upstream against the pinned commit for these 15 skills only. Changes are adopted only after review, then released as a new version.

Maintained by Nimblechapps. Original skills by Corey Haines, MIT licence.
