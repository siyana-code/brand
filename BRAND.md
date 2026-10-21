# Siyana Code — Brand Guide

The public identity of **Siyana Code**, the solo software studio of Rasindu Appuhami.

- **Tagline:** Open source, built in the open.
- **Site:** https://siyanacode.tech
- **GitHub:** https://github.com/siyana-code
- **Contact:** rchkaushalya@gmail.com · Sri Lanka

---

## 1. The mark

The mark is a rounded tile in the brand accent, holding a `< • >` glyph — code
brackets with a seed between them. It says *code* at a glance and carries the
warmth of the palette.

| Asset | Use |
| --- | --- |
| `logo/tile.svg` | Avatars, favicons, app icons, social |
| `logo/mark.svg` | Inline mark on light or dark surfaces (`currentColor`) |
| `logo/logo.svg` | Horizontal lockup (tile + wordmark) |
| `logo/logo-mono.svg` | One-colour lockup for print or single-ink use |
| `logo/avatar-512.png` | GitHub / social avatar (circular crop) |
| `logo/favicon.svg` | Browser tab icon |

**Clear space:** keep at least ¼ of the tile's width clear on every side.
**Minimum size:** 16 px for the mark alone, 24 px for the lockup.
**Backgrounds:** the tile works on light and dark; the plain mark inherits the
text colour, so it stays legible on either.

**Do:** use the tile for avatars and icons. Use the plain mark inline.
**Don't:** recolor the tile, stretch it, add effects, or place the plain mark on
a low-contrast background.

---

## 2. Colour

Warm minimalist. The palette is deliberately quiet so the work speaks.

### Light

| Role | Token | Hex |
| --- | --- | --- |
| Background | `--bg` | `#F5F3F0` |
| Surface | `--surface` | `#EBE7E2` |
| Surface (raised) | `--surface-2` | `#E3DDD5` |
| Text | `--text` | `#2A2724` |
| Muted text | `--muted` | `#8A8378` |
| Accent | `--accent` | `#8B6F5C` |
| Accent (hover) | `--accent-hover` | `#5C4A3D` |
| Border | `--border` | `#D8D2CA` |

### Dark

| Role | Token | Hex |
| --- | --- | --- |
| Background | `--bg` | `#1C1A18` |
| Surface | `--surface` | `#24211E` |
| Surface (raised) | `--surface-2` | `#2D2924` |
| Text | `--text` | `#F5F3F0` |
| Muted text | `--muted` | `#A79E93` |
| Accent | `--accent` | `#C9A98F` |
| Accent (hover) | `--accent-hover` | `#DCC0A8` |
| Border | `--border` | `#3A352F` |

Dark mode follows `prefers-color-scheme`. The accent lightens in dark mode so
contrast is preserved.

---

## 3. Typography

| Role | Family | Notes |
| --- | --- | --- |
| Display & headings | **Fraunces** | Optical-size serif. Weights 400–700. |
| Body & UI | **Inter** | Weights 400–700. |
| Code | System monospace | `ui-monospace`, Cascadia Code, Consolas. |

Headings use tight tracking (`-0.02em`). Body copy is 16 px with a line height
of 1.6–1.7.

---

## 4. Voice

- **Plain and precise.** No hype, no "revolutionary", no exclamation marks.
- **Show the work.** Prefer a repository, a test, or a decision record over an adjective.
- **Honest about status.** Say "in progress" and what is missing. Gaps are visible, not implied.
- **Warm, not cute.** The palette is friendly; the writing is not.

---

## 5. Where things live

| Path | Contents |
| --- | --- |
| `logo/` | Mark, tile, lockups, favicons, OG image, avatar |
| `profile/README.md` | The GitHub organisation landing page (goes in `siyana-code/.github`) |
| `BRAND.md` | This document |
