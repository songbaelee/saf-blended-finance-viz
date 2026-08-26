# SAF Blended Finance Structure — Animated Morph

An animated SVG diagram that starts from the KOICA IPS Call for Proposals'
Annex 2 "Model 2" business-model template and morphs, stage by stage, into
SAF's actual capital structure.

## Viewing

Open `index.html` directly in a browser, or via GitHub Pages once enabled
(Settings → Pages → deploy from `main` branch, root).

## Structure

- `index.html` — single-file page: SVG diagram + GSAP timeline animation
- `assets/` — reserved for any separate images/exports if needed later

## Stages (planned)

1. Starting point: CFP Annex 2, Model 2 (bottom-left variant) — Technical
   Assistance Facility + Private Capital + First-Loss Capital inside one
   Blended Finance Structure box
2. Private Capital box pulled out, replaced by two boxes: Senior Debt,
   Junior Debt
3. Portfolio-level view: 15 project boxes appear to the right; SAF's
   capital (Senior + Junior, undifferentiated at this level) splits
   pro rata into 15 pieces, one per project
4. Private capital reappears — not as SAF's own capital, but as separate
   local/commercial capital raised independently by each of the 15 Local
   Partners, shown sitting on top of each project-level SAF slice

Additional stages to be added as they're confirmed.

## Status

Early scaffold — stage 1 only. Password-gating and any public/private
access decisions are deferred until content is finalized.
