# Brand Spiral Work Index

The studio's work index drawn as one continuous spiral: 428 engagements, each a point on the curve, annotated in mono on a near-black ground.

Two geometries over the same 428 points, because the record supports two honest questions:

- **Time** — radius grows with chronological position; reads as output accumulating. Only 81 of 429 projects carry a real deadline, so year is mostly the date a project entered the record. Order is broadly right; exact years are not.
- **Depth** — radius is the Nth engagement with that partner, angle is the partner. Each relationship becomes a spoke whose length is its depth. Immune to the date problem.

Switching tweens between them: the work doesn't change, the question does.

## v2.0

- **List view** — native `<details>`, keyboard-navigable and crawlable without JS, ordered by depth of relationship.
- **Channel strip** — a colour bar per solution domain with its own project count.
- **Filter state** — active filters shown as dismissable chips.
- **Tactics** — the actual moves made per engagement, each carrying its solution's colour. 352 projects carry them from the record; 42 were inferred from titles; 35 deliberately left blank.
- **Gaps panel** — per-engagement data-quality caveats, stated rather than hidden.
- **Pinned record** — click an engagement to hold its full record open.

Single self-contained HTML file, no build step. Originally `BrandSpiralWorkIndexIdea.html`.

Published to YF Builds from Claude Code.
