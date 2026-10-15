# Connor’s Humanizer

A writing and editing skill by Connor Yost for natural, specific prose. It includes a personalized voice guide, a catalog of common formulaic writing patterns, and source notes. It preserves meaning, evidence, technical terminology, and the writer’s judgment.

## Download

[Download the complete skill ZIP](https://github.com/yostboy6/connor-humanizer/raw/refs/heads/main/connor-humanizer.zip).

Extract the ZIP to get a `connor-humanizer` folder. Keep its files and subfolders together; `SKILL.md` uses the reference files. The repository’s **Code → Download ZIP** option also includes the source files and this README.

## Install in Codex

Copy the extracted `connor-humanizer` folder into `~/.codex/skills/` (or your configured Codex skills directory). Start a new session if needed for discovery, then invoke `$connor-humanizer` with the text and intended audience.

Example: “Use $connor-humanizer to revise this email for a colleague. Preserve the facts and keep it concise: [paste draft].”

## Use with Claude or another assistant

For a skill-compatible environment, place the complete folder in that environment’s supported skills directory. Otherwise, provide `SKILL.md` and the three files in `references/` as context and ask the assistant to follow the skill. `agents/openai.yaml` is optional Codex display metadata.

## Adapt the voice

The defaults reflect Connor’s preferences, including no em dashes. For another writer, edit `references/connor-voice.md` and any Connor-specific instructions in `SKILL.md`. Supply the writer’s audience, purpose, and preferred examples. If renaming the skill, update the frontmatter name and `agents/openai.yaml` prompt together.

## Package contents

- `SKILL.md`: core writing and editing instructions.
- `references/connor-voice.md`: personal voice and genre guidance.
- `references/pattern-catalog.md`: patterns to assess in context, with revision guidance.
- `references/sources.md`: bibliography and maintenance notes.
- `agents/openai.yaml`: Codex display name and default prompt.

No scripts, API keys, or additional software dependencies are required by the skill itself. External bibliography links are reading material, not runtime dependencies. The skill does not establish AI authorship or guarantee AI-detector results. Review factual claims and citations before using generated prose.
