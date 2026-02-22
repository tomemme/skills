---
name: movie-context
description: Enrich any movie or TV scene with accurate historical, political, environmental, cultural, filming, and thematic context. Always verify facts before answering. Ideal for pausing mid-watch to go deeper.
---

# Movie Context

Use this skill to quickly enrich a scene with grounded real-world context and production facts.

## Core Rules (follow every single time)

1. **Always start with browser tool**
- Search reliable sources first (IMDb trivia/locations pages, Wikipedia, official director/studio archives, Kubrick.org, BFI, major film journalism).
- For filming locations, check IMDb "Filming Locations" plus at least one production/making-of source.
- For animals/props, search combinations like `real animals used in <movie> <scene>` and `human actors in suits <movie>`.

2. **Cross-verify with model knowledge**
- After browsing, cross-check against internal model knowledge (especially for major classics).
- If sources and model memory disagree, trust the most reliable/current source and explicitly note the conflict.

3. **Key things to always cover**
- Exact filming locations (soundstage vs real places, notable techniques like front-projection, miniatures, CGI).
- Real animals vs human actors in suits/costumes vs props/animatronics.
- Historical/political/war timeline for the setting.
- Climate/environment and relevant real-world events around that time/place.
- Clear tie-in to themes (evolution, technology, colonialism, human nature, etc.).

4. **Output format**
- Keep response fast to scan between scenes.
- Always include sections in this order:
  - **Filming Location**
  - **Real Animals / Props**
  - **Historical / Environmental Context**
  - **Thematic Tie-In**
  - **Sources**
- End with: `Want deeper dive on any part (book recs, maps, related docs)?`

## Output Template

```markdown
## Filming Location
- ...

## Real Animals / Props
- Real animals:
- Human actors in suits/costumes:
- Props/other:

## Historical / Environmental Context
- Timeline:
- Why it matters:

## Thematic Tie-In
- 1-2 sentences max.

## Sources
- [Source title](URL)
- [Source title](URL)

Want deeper dive on any part (book recs, maps, related docs)?
```

## Trigger Examples

- `movie context on the Dawn of Man scene in 2001`
- `context on the Africa war part`
- `enrich the opening of 2001: A Space Odyssey`

## Reliability Priority

- Speed + accuracy over everything.
- Never guess.
- If unclear, explicitly state what was checked and what remains uncertain.
