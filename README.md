# Consistent Character Talking Video Maker

A VideoExpress workflow for a consistent talking character. Upload a realistic or animated character reference, provide the setting and script, and receive a complete scene packet for manual VideoExpress production. It supports comedy, teaching, explainers, presenter videos, AIE advertising and Prepspire advertising.

Every request produces one detailed Markdown packet with sequential scene-by-scene image prompts followed by the matching image-to-multishot VideoExpress prompts for manual production.

## Defaults

- Runtime: user specified; default 30 seconds to 2 minutes
- Format: 9:16 by default; 16:9 when requested
- Style: realistic or animated talking character, as requested
- Voices: stable Indian-accented English voices
- Output: full script, character/series locks, image prompts, paired VideoExpress prompts, sources or teaching notes, and edit checklist

## Character and performance continuity

Use stable character IDs, series IDs and location IDs. Map each uploaded image to a character, prop or setting before writing prompts. Freeze a complete character bible and repeat it verbatim in every scene prompt. The voice registry records the voice name/ID, accent, pitch, pace, energy, intonation and mannerisms. Reuse the same voice and performance profile unless the user explicitly changes it.

## Getting started

Open SYSTEM_PROMPT.md in a browser-capable assistant, then provide your topic or story, style, optional reference images, intended use, length and whether this belongs to an existing series.

## Files

| File | Purpose |
|---|---|
| SYSTEM_PROMPT.md | Full production instructions |
| SYSTEM_PROMPT_COMPACT.md | Compact assistant instructions |
| PLAYBOOK.md | Detailed workflow foundation |
| VOICE_REGISTRY.md | Persistent character and voice records |
| SERIES_REGISTRY.md | Persistent series and cast records |
| templates/episode-output.md | Required Markdown output format |

Adapted from [VideoExpress Consistent Character Talking Video](https://github.com/ai-playbooks/videoexpress-consistent-character-talking-video), with a GitHub-maintained Markdown packet for manual VideoExpress production.
