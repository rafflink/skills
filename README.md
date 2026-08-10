# Agent Skills

My agent skills, installed globally for opencode.

## Skills

- `ask-matt` - Router over the user-invoked skills.
- `code-review` - Review changes since a fixed point along Standards and Spec axes.
- `codebase-design` - Shared vocabulary for designing deep modules.
- `diagnosing-bugs` - Disciplined loop for hard bugs and performance regressions.
- `domain-modeling` - Build and sharpen a project's domain model.
- `grill-with-docs` - Interview to sharpen a plan/design while building ADRs and glossary.
- `implement` - Build work described by a spec or set of tickets.
- `improve-codebase-architecture` - Scan a codebase for deepening opportunities.
- `prototype` - Build throwaway prototypes to answer design questions.
- `research` - Investigate against primary sources, captured as cited Markdown.
- `resolving-merge-conflicts` - Resolve git conflicts by intent, never `--abort`.
- `setup-matt-pocock-skills` - Configure the repo for the engineering skills.
- `tdd` - Test-driven development with a red-green-refactor loop.
- `to-spec` - Turn the current conversation into a spec.
- `to-tickets` - Break a plan into tracer-bullet tickets.
- `triage` - Move issues through a triage state machine.
- `wayfinder` - Plan huge work as a map of decision tickets.
- `wizard` - Generate an interactive bash wizard for human-only steps.

## Productivity

- `grill-me` - Get relentlessly interviewed about a plan or design.
- `grilling` - The reusable interview primitive.
- `handoff` - Compact the conversation into a handoff document.
- `teach` - Teach a skill over multiple sessions.
- `to-questionnaire` - Turn a decision into a Markdown questionnaire.
- `wait-what` - Re-pitch a message with missing context.
- `writing-for-agents` - Writing documents for agents.

## General

- `claude-handoff` - Hand off work between agents.
- `git-guardrails-claude-code` - Git safety guardrails.
- `loop-me` - Structured feedback loops.
- `migrate-to-shoehorn` - Migration helper.
- `scaffold-exercises` - Scaffold coding exercises.
- `setup-pre-commit` - Pre-commit setup.
- `writing-beats` / `writing-fragments` / `writing-shape` - Writing workflow skills.

## Installation

Installed from [mattpocock/skills](https://github.com/mattpocock/skills) via the
skills CLI. Update with:

```
npx skills@latest update --global
```

opencode auto-loads skills from `~/.agents/skills`.