# ADISCO DINO JUMP — generated visual concept assets

This ZIP contains **three original AI-generated pixel-art concept atlases** created for the ADISCO DINO JUMP project. They are visual source material for an asset-production pass, not a finished import-ready sprite library.

## Contents

- `sprite_sheets/01_player_and_teacher_concept_atlas.png` — player poses and four fictional teacher designs.
- `sprite_sheets/02_full_game_asset_concept_atlas.png` — broad concept board showing the player, teachers, 11 labeled housemaster concepts, headmaster, dining power-ups, obstacles, campus-inspired scenes, UI, effects and badges.
- `sprite_sheets/03_asset_catalog_concept_atlas.png` — alternate catalog-style concept board covering the same broad categories.
- `metadata/manifest.json` — file inventory, dimensions, formats, and production status.
- `metadata/animation_metadata.json` — explicit status record; no frame sequences have been sliced or validated.

## Technical inspection

All three files are PNG images. The generated images contain visible backgrounds (including a checkerboard pattern in one atlas); they are **not confirmed transparent PNG sprites**. They are not separated into individual frame files, and their visual grid spacing is not sufficiently regular to claim reliable automated slicing. The images should therefore be treated as reference atlases, not dropped directly into a Canvas sprite renderer as frame sheets.

## What is and is not delivered

| Item | Delivered |
|---|---:|
| Original generated concept atlas PNGs | 3 |
| Individual game-ready character PNGs | 0 |
| Validated animated characters | 0 |
| Validated horizontal animation sprite sheets | 0 |
| Animation metadata describing verified frame coordinates | 0 |
| Transparent-background individual sprites | 0 |

The atlas artwork depicts multiple animation poses, but pose depictions inside a concept board do not constitute a validated animation sequence. Character consistency, frame dimensions, transparent backgrounds, and frame alignment still need an artist/technical-art pass.

## Adisadel house-name verification

The official Adisadel College website describes **ten houses** and lists Hamlyn, Elliott (also commonly written Elliot), Canterbury, Knight, Jubilee, Ebiradze, Le-Maire, Quaque, Aglionby, and Thomas Jonah. Ato Mould is not in that official ten-house list. It is included as a requested *provisional visual concept* in the generated atlas, not represented here as a verified current house. Confirm its present status with the school before using it as a canonical in-game house.

## Environment accuracy

The campus artwork is stylized and inspired by the supplied location names. It is not a photogrammetrically or architecturally verified recreation of the Clock Tower, 83 Steps, buildings, dining hall, or Sahara field. Use official photographs and on-site references for a faithful final environment pass.

## Recommended next production pass

1. Rebuild each character as a clean, isolated transparent sprite at one fixed canvas size.
2. Create and review frame-by-frame loops (player run should have at least eight frames).
3. Export individual PNG frames, horizontal sheets, and coordinate metadata.
4. Replace concept campus panels with reference-matched parallax layers.
5. Validate every PNG's alpha channel, frame bounds, naming, and duplicate status before shipping.

## Sources consulted for school context

- Adisadel College, Houses: https://adisadelcollege.net/houses/
- Adisadel College, Campus Tour: https://adisadelcollege.net/campus-tour/
- Adisadel College, About Adisadel College: https://adisadelcollege.net/about-adisadel-college/

The official houses page is an older page and contains historical/current-as-of-2023 housemaster details; this pack does not treat those staff names as current. All faculty and boss characters are fictional.
