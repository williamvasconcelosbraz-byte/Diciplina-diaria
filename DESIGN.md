---
name: Momentum Habit System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  title:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-counter:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for intentionality, clarity, and daily micro-triumphs. Designed primarily for ambitious individuals seeking steady personal transformation through behavioral psychology, the visual narrative balances uncompromising functional minimalism with tactile, rewarding micro-feedback.

The aesthetic fuses **Modern High-Contrast Precision** with **Tactile Performance Design**:
- **Atmosphere:** Calm, deliberate, and noise-free. Avoids sensory overload during morning check-ins while delivering dopamine-rich validation upon task completion.
- **Visual Weight:** Deep slate grounding meets razor-sharp typography and hyper-targeted motivational highlights. The environment recedes so daily commitments take center stage.
- **Physicality:** Interacting with inputs, checks, and mood sliders feels tangible—leveraging responsive transitions, subtle border glows, and crisp toggle movements that honor the phrase *"Pequenas mudanças, grandes resultados"*.

## Colors

The palette relies on high-contrast role division to ensure instant scanability on mobile devices under direct ambient light or late-night bed routines.

### Palette Architecture
- **Primary (`#0F172A` - Midnight Slate):** Anchor tone for primary typography, structural icons, and high-emphasis states. Delivers authority without the harshness of pure black.
- **Secondary (`#059669` - Emerald Vitality):** Reserved strictly for resolution, completions, perfect consistency marks, and forward momentum. Paired with a soft mint wash (`#ECFDF5`) for container backgrounds.
- **Tertiary (`#F59E0B` - Amber Flare):** Dedicated to flame streaks, energy levels, mood triggers, and proactive warnings. Accented alongside a warm coral (`#F43F5E`) for mental strain and rest recovery markers.
- **Neutral (`#64748B` - Slate Core):** Supporting textual hierarchy, meta captions, inactive track strokes, and dividers.
- **Background Canvas & Surfaces:** 
  - Canvas: `#F8FAFC` (pure off-white slate)
  - Card Surface: `#FFFFFF` (pure crisp contrast)
  - Dark Mode Inversion Surface: `#111827` base with `#1E293B` containers.

## Typography

Typography establishes an unyielding structural grid using **Inter** across all roles. Tight tracking on display and headline tiers produces a disciplined, modern athletic app presence, while tabular numerals guarantee flicker-free metric increments.

- **Display & Headline:** Used for dashboard daily greetings, macro completion summaries, and streak tallies. Features aggressive negative tracking to eliminate loose visual rhythm.
- **Body & Meta:** Clean, legible, with balanced vertical line heights optimized for glanceable task reading at 390px viewport constraints.
- **Label & Data:** All uppercase variants (`label-sm`) require `letterSpacing: 0.04em` to balance legibility for habit frequency tags and status stamps.

## Layout & Spacing

The layout is optimized specifically around a mobile-first standard viewport baseline of **390px** width with safe-area hardware insets.

### Layout Rules
- **Grid Architecture:** 4-column fluid mobile grid with `1.25rem` (20px) outer margins and `1rem` (16px) gutters. Cards span either the full 4 columns or split evenly into 2-column modules for split metric tracking (e.g., Daily Streak / Energy Level).
- **Vertical Spacing Rhythm:** Component interiors operate on strict 4px/8px intervals. Task items stack with `0.5rem` gaps to permit dense scanning without touch target collision.
- **Thumb Zone Anchor:** Bottom navigation and primary action triggers sit within a fixed floating lower boundary padded with `1.25rem` horizontal margin and elevated `env(safe-area-inset-bottom)`.
- **Responsive Adaptability:** On tablet and desktop viewports, content max-width clamps strictly at `480px` centered within the viewport canvas, preserving the intimate focus of a personal handheld agenda.

## Elevation & Depth

Visual hierarchy uses a refined hybrid of **tonal layering** and **low-contrast micro-borders**, rejecting muddy drop shadows in favor of crisp delineation.

- **Level 0 (Canvas Base):** Flat `#F8FAFC`. Zero elevation.
- **Level 1 (Card Default):** `#FFFFFF` surface enclosed by a 1px border of `#E2E8F0`. Shadow is microscopic: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`.
- **Level 2 (Active / Raised Task):** Used when dragging or pressing a task item. Background shifts slightly up; border tone strengthens to `#CBD5E1`; shadow transforms to `0 8px 16px -4px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals / Floating Bottom Bars):** `#FFFFFF` surface with heavy backdrop blur (`backdrop-filter: blur(12px)`) when semi-translucent; bounded by `0 20px 25px -5px rgba(15, 23, 42, 0.1)`.
- **Completed Habit Depth:** Tasks completed during a session drop visually into the surface: border shifts to a subtle `#D1FAE5`, background adopts a soft `#F0FDF4` tint, and shadows vanish entirely to signify resolved weight.

## Shapes

The design system employs **Roundedness Level 2**, establishing balanced, approachable, yet engineered contours that mimic premium hardware interfaces.

- **Standard Containers & Cards (`rounded-lg` - 1rem / 16px):** Primary habit cards, weekly streak matrix containers, and mood reflection panels.
- **Interactive Controls (`rounded` - 0.5rem / 8px):** Checkbox tap zones, date selector nodes, and secondary pill chips.
- **Pill Badges (`9999px`):** Reserved exclusively for dynamic status markers (e.g., streak counters, category tags, mood indicators) and primary bottom action bars.

## Components

### 1. Habit Checklist Item (Hero Component)
- **Container:** Pure white card, 1px `#E2E8F0` border, `16px` border-radius, `14px 16px` internal padding. Minimum height `64px` for touch accessibility.
- **Interaction Target:** Custom 26px checkbox aligned left. Inactive state: 2px stroke of `#CBD5E1`, transparent center. Active (checked) state: Smooth scale-down pop (0.9 to 1.0) filling with `#059669`, revealing a crisp white vector checkmark.
- **Text Reaction:** Upon completion, habit title transitions to `#94A3B8` with a clean strikethrough animation.
- **Streak Indicator:** Right-aligned mini badge showing the tertiary amber flame icon with tabular counter text.

### 2. Buttons
- **Primary Action (Add Habit / Complete Day):** Solid `#0F172A` fill, white text, bold label. Height `48px`, `rounded-full` or `rounded-lg`. Active tap state applies `scale(0.98)` with slight opacity decrease (`0.92`).
- **Success Confirm Action:** Solid `#059669` fill with subtle emerald shadow halo (`0 4px 14px rgba(5, 150, 105, 0.35)`).
- **Ghost / Tertiary:** Borderless, `#64748B` typography, hovering into `#0F172A` with `#F1F5F9` background fill.

### 3. Mental State & Mood Tracker
- **Segmented Range / Mood Cards:** 5-step discrete horizontal selector (Exhausted, Low, Balanced, Driven, Unstoppable).
- **Styling:** Inactive options present as monochrome slate outlines. Active choice highlights with warm tertiary amber (`#F59E0B`) or coral glow, accompanied by an energetic numeric level badge.

### 4. Chips & Category Filters
- **Form:** `32px` height, `rounded-full`, padding `0 12px`.
- **States:** Inactive chips feature `#F1F5F9` surface with `#475569` text. Active filter toggles to solid `#0F172A` background with crisp white typography.

### 5. Input Fields
- **Container:** Height `48px`, background `#FFFFFF`, border `1.5px` solid `#E2E8F0`, padding `0 16px`.
- **Focus State:** Border transitions cleanly to `#0F172A` with a distinct `0 0 0 3px rgba(15, 23, 42, 0.08)` outline ring. Placeholder styled in muted `#94A3B8`.

### 6. Consistency Matrix (Weekly Strip)
- **Form:** 7-day horizontal calendar rail anchored at the top of the interface.
- **Node Design:** Day abbreviations in `label-sm` above a circular node (`36px`). Current day highlighted with an active stroke; completed days filled with `#059669` dot; missed days displaying a faint `#CBD5E1` dash.