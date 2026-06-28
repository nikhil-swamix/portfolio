# AGENTS.md

## Purpose
This repository is a curated portfolio snapshot for `nikhil-swamix`.

## What was discovered during triage
- The GitHub account contains a large mix of:
  - original public projects
  - private client work
  - public forks / mirrors
  - older academic projects
- The strongest public portfolio candidates were not necessarily the most starred repos; they were the most credible combinations of:
  - relevance
  - originality
  - code volume
  - recent activity
  - measurable adoption signals (stars/forks)

## Ranking signals that worked well
When selecting featured repos, use this order of importance:
1. Original public work over forks
2. Clear product or engineering value
3. Recent maintenance/activity
4. Stars and forks as popularity / usefulness signals
5. Commit count and source LOC as depth signals

## Best-featured projects found
- `TerminalProfileManager` — strongest public signal; utility with 21 stars and 26 commits
- `Devops-Showcase` — useful for presentation of DevOps collaboration work
- `IndiaTools` — strongest code-depth-to-popularity ratio among smaller Python libraries
- `MongEasy` — practical JS database utility
- `sambanova-copilot` — relevant AI assistant project
- `PDF2Text` — clear utility/project value
- `ComputerGraphicsProject` — solid academic implementation
- `llm-services` — infrastructure-focused LLM tooling repo

## Metrics gathered
- Total repos analyzed: 92
- Public repos: 71
- Private repos: 21
- Original public repos: 55
- Public forks: 16
- Featured set size: 8
- Featured commits total: 134
- Featured source LOC total: 40,435

## Commands that were useful
- List repos:
  - `gh repo list nikhil-swamix --limit 200 --json ...`
- Get commit counts without cloning full history:
  - GitHub GraphQL `defaultBranchRef.target.history.totalCount`
- Estimate LOC:
  - shallow clone + count tracked source/config files while excluding build/vendor directories

## Important caveats
- LOC is approximate, not a strict audit number.
- Private repos were intentionally excluded from the public portfolio.
- Some repos should be avoided in a public showcase because they are forks, mirrors, or not representative of professional work.

## Recommended next improvements
- Add screenshots and short case studies for the featured projects
- Add badges for stars, commits, and language
- Create a GitHub Pages landing page
- Add a resume PDF that links back to this portfolio repo
