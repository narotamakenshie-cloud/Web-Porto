---
name: Nocturne Editorial
colors:
  surface: '#131317'
  surface-dim: '#131317'
  surface-bright: '#39393d'
  surface-container-lowest: '#0e0e12'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#2a292e'
  surface-container-highest: '#353439'
  on-surface: '#e4e1e7'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e4e1e7'
  inverse-on-surface: '#303034'
  outline: '#958ea0'
  outline-variant: '#494455'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3b0091'
  primary-container: '#9f78ff'
  on-primary-container: '#330080'
  inverse-primary: '#6d38dc'
  secondary: '#d2bcff'
  on-secondary: '#382463'
  secondary-container: '#4f3b7b'
  on-secondary-container: '#c1a9f2'
  tertiary: '#d4bbff'
  on-tertiary: '#3d1876'
  tertiary-container: '#a17fdf'
  on-tertiary-container: '#360e6f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#550fc4'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bcff'
  on-secondary-fixed: '#230b4d'
  on-secondary-fixed-variant: '#4f3b7b'
  tertiary-fixed: '#ebdcff'
  tertiary-fixed-dim: '#d4bbff'
  on-tertiary-fixed: '#260058'
  on-tertiary-fixed-variant: '#55338e'
  background: '#131317'
  on-background: '#e4e1e7'
  surface-variant: '#353439'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  stat-counter:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  stat-counter-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system pairs dark-mode native immersion with crisp, minimalist editorial discipline. It serves high-end technical, developer-centric, or analytical platforms where focus, precision, and authority are essential. 

The aesthetic is deep, calm, and deliberate. Near-black canvas foundations prevent eye fatigue, while structured typographic scales, whisper-thin container strokes, and vivid violet highlights create an elevated, museum-grade technical feel. The emotional response should be one of confidence, silent power, and effortless clarity—avoiding aggressive gaming neon in favor of calculated, luminous optical hierarchy.

## Colors
The palette is built upon deep obsidian darkness punctuated by high-potency violet accents.

- **Canvas & Surfaces:**
  - Base Background: `#0B0B0F` (near-black foundation canvas).
  - Primary Surface: `#140C24` (dark, purple-tinted card and container surface).
  - Secondary Surface: `#2A1454` (accented containment, hover states, and active card segments).
  - Border Subdued: `#231B36` (structural, precise 1px wireframes separating information tiers).

- **Accents:**
  - Primary Accent: `#8756F7` (used selectively for key actions, interactive states, focus rings, and high-priority metrics).
  - High Accent: `#B794F6` (used for small pill indicators, high-contrast links, and active icon glyphs).

- **Typography & Foreground:**
  - Text Primary: `#FFFFFF` (high-contrast clarity for headings and vital data).
  - Text Secondary: `#AAAAAA` (muted, technical secondary reading level).
  - Text Dim: `#645C75` (metadata, keyboard shortcuts, and disabled states).

## Typography
The system uses a deliberate pairing of `Space Grotesk` for architectural structure and `Plus Jakarta Sans` for reading clarity.

- **Space Grotesk** drives headlines, data readouts, numerical stat counters, badges, and labels. Its subtle geometric quirks supply a technological authority without feeling overtly industrial.
- **Plus Jakarta Sans** delivers humanist neutral warmth and high legibility across paragraphs, tooltips, forms, and complex tabular reading contexts.
- **Editorial Stat Treatment:** Numeric dashboards and metrics leverage the `stat-counter` scale rendered in pure `#FFFFFF`, paired immediately below with an uppercase `label-sm` in `#AAAAAA` or `#B794F6` with expanded letter spacing (`0.06em`).

## Layout & Spacing
The layout adheres to a 12-column responsive fluid grid on desktop (`1200px`+ max canvas constraint with centered gutters) transitioning into 8 columns on tablet and 4 columns on mobile. 

Editorial negative space governs the layout rhythm. Rather than crowding content, sections breathe with generous outer padding (`space-xl` or greater) and strict structural alignment. Spacing between atomic elements uses a disciplined base-4 system:
- Micro spacing (`space-xs`, `space-sm`) separates paired text labels, icon-text clusters, and inner pill badge padding.
- Medium spacing (`space-md`, `space-lg`) dictates form element separation, card interior padding, and horizontal list gaps.
- Structural layout margins (`margin`, `margin-mobile`) lock content away from canvas extremes while preserving full-bleed background continuity.

## Elevation & Depth
Elevation is maintained primarily through **tonal layering** and **refined 1px structural outlines**, rather than heavy drop shadows.

1. **Surface Tiers:**
   - **Canvas (Level 0):** `#0B0B0F` — The infinite depth.
   - **Cards & Primary Modules (Level 1):** `#140C24` backed by a 1px solid stroke of `#231B36`.
   - **Popovers, Dropdowns & Modals (Level 2):** `#1A102E` with 1px border `#2A1454` and a faint ambient glow: `0px 16px 40px -8px rgba(135, 86, 247, 0.12), 0px 4px 12px rgba(0, 0, 0, 0.6)`.

2. **Specular Lighting & Edge Highlights:**
   Interactive cards and elevated panels use subtle inner hairline borders (`inset 0 1px 0 rgba(255, 255, 255, 0.05)`) along the top edge to emulate soft overhead ambient studio illumination against the deep purple background.

## Shapes
A hybrid architectural shape language is enforced:
- **Core Containers, Panels, & Cards:** Use subtle, crisp curvature (`roundedness: 1`, translating to `4px` base, with `8px` for large cards and modals). This keeps the interface structured, clinical, and editorial.
- **Pill Badges, Chips, & Primary Buttons:** Break the rectilinear rhythm by using full pill rounding (`9999px` radius). This contrast ensures interactive and high-status elements immediately jump forward from the architectural grid.

## Components

### Buttons
- **Primary:** Full pill (`9999px` radius). Solid `#8756F7` fill, text `#FFFFFF` in `Space Grotesk` Medium (`label-md`). Hover state transitions to `#9B6FFA` with subtle purple outer bloom (`box-shadow: 0 0 16px rgba(135, 86, 247, 0.4)`).
- **Secondary / Ghost:** Full pill. Background `#140C24`, 1px border `#231B36`, text `#FFFFFF`. Hover changes border to `#8756F7` and background to `#2A1454`.

### Badges & Pill Tags
- Fully rounded (`9999px`) badges.
- Background: `rgba(135, 86, 247, 0.12)`.
- Border: `1px solid rgba(135, 86, 247, 0.3)`.
- Text: `#B794F6`, uppercase `label-sm` with active letter-spacing.
- Often paired with an inner 6px solid dot indicator for live state representation.

### Cards & Stat Blocks
- Background: `#140C24`.
- Border: `1px solid #231B36`.
- Corner Radius: `8px`.
- Padding: `1.5rem` (`space-lg`).
- Stat Counter cards display the metric in `stat-counter` styling (`#FFFFFF`), with contextual mini sparklines or percentage pills positioned top-right.

### Form Inputs
- Background: `#0E0818`.
- Border: `1px solid #231B36`.
- Corner Radius: `4px`.
- Padding: `0.75rem 1rem`.
- Text: `#FFFFFF`, Placeholder: `#645C75`.
- Focus state: Border transitions instantly to `#8756F7` with a non-blurring `0 0 0 1px #8756F7` outline.

### Selection Controls (Checkboxes & Radios)
- Standard `18px` boxes with `4px` radius (checkbox) or circular (radio).
- Unchecked: `#140C24` fill with `#231B36` border.
- Checked: `#8756F7` fill with crisp white geometric icon check or centered circular pip.

### Lists & Tables
- Borderless rows separated by `1px solid #231B36` divider lines.
- Hovering a row applies a smooth transition to background `#180F2B`.
- Header rows utilize `Space Grotesk` `label-sm` in `#AAAAAA` with uppercase treatment.