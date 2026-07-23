# Bible Stories Studio

Central production repository for a premium stylized 3D animated Bible-story series.

## Single source of truth

1. `01_Master_Bible/` contains the creative and production rules.
2. `02_Style_Bible/Approved/` contains approved visual references.
3. `03_Characters/` contains locked character packs.
4. `04_Environments/` contains recurring locations.
5. `05_Props/` contains reusable objects.
6. `06_Episodes/` contains a complete production pack per episode.
7. `07_Templates/` contains reusable documents.
8. `09_Exports/` is for final delivery files.

## Current status

- Master Bible v1.0 created.
- Premium stylized cinematic 3D animation approved.
- David shepherd style frame approved.
- Photorealistic storybook concept rejected.
- First active episode: EP001 — David and Goliath.
- Next production task: lock David's character design.

## Working rule

Never overwrite approved assets silently. Create a new version and update the relevant changelog.

Example:

`David_Front_v1.png` → `David_Front_v2.png`

Only one version should be marked `APPROVED` in the asset manifest.
