---
name: Sven D. Manilhig Portfolio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c4c5d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8e90a0'
  outline-variant: '#434655'
  surface-tint: '#b7c4ff'
  primary: '#b7c4ff'
  on-primary: '#002682'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#2151da'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ffb59c'
  on-tertiary: '#5c1900'
  tertiary-container: '#a73400'
  on-tertiary-container: '#ffc9b7'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832700'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.025em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.05em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The brand personality embodies grounded technical competence, deliberate simplicity, and fresh engineering rigor. Tailored for hiring managers, engineering leads, and technical recruiters, the aesthetic projects discipline and structured problem-solving rather than decorative vanity.

The design movement is **Corporate / Modern** merged with **Technical Minimalism**:
- A slate and charcoal dark canvas that eliminates screen glare and frames code snippets, system architectures, and live project demos with precision.
- Electric cobalt and deep tech blue accents signaling focus, clarity, and foundational stability.
- An editorial cadence powered by dense, rhythmic layouts, subtle micro-borders, and high-readability typographic hierarchies.
- Overall tone: pragmatic, confident, organized, and authentic.

## Colors

The color system establishes an organized dark mode environment rooted in cool slates and anchored by reliable tech blues:

- **Primary (`#1d4ed8`)**: Classic engineering cobalt blue, used for primary calls to action, active navigation states, interactive card highlights, and key metric emphasis.
- **Secondary (`#3b82f6`)**: Lighter electric azure, reserved for focus rings, hover states on interactive chips, secondary links, and inline code tags.
- **Surface & Backgrounds**:
  - Base canvas: `#0b0f19` (deepest ink charcoal).
  - Surface Tier 1 (Cards, Navigation bars): `#111827` (slate-900).
  - Surface Tier 2 (Elevated modals, code blocks, active inputs): `#1e293b` (slate-800).
- **Borders & Separators**:
  - Subtle borders: `rgba(255, 255, 255, 0.08)`.
  - Emphasized borders: `rgba(59, 130, 246, 0.35)`.
- **Typography & Content**:
  - Primary text: `#f8fafc` (slate-50) for immediate legibility.
  - Secondary text: `#94a3b8` (slate-400) for descriptions, timestamps, and tech-stack details.
  - Muted text: `#64748b` (slate-500) for metadata and labels.

## Typography

The type system is strictly standardized around **Inter** to ensure maximum typographic neutrality, systematic rhythm, and high visual legibility across technical specifications and interface copy:

- **Headings**: Use weights `600` and `700` with subtle negative letter spacing (`-0.01em` to `-0.02em`) to maintain a clean, confident silhouette without visual distortion.
- **Body Content**: Standardized at `16px` (`body-md`) with a `1.5` line height (`24px`) for optimal readability against dark surfaces.
- **Technical & Stack Tags**: Utilize `label-md` and `label-sm` with slight positive tracking (`0.025em` to `0.05em`) for uppercase badge treatments, skill groupings (e.g., PHP, MySQL, Git), and metadata headers.

## Layout & Spacing

The layout employs a structured 12-column fluid grid system bounded by a max-width container of `1200px`:

- **Desktop (≥ 1024px)**: 12 columns, `1.5rem` (`24px`) gutters, and `2rem` (`32px`) canvas margins.
- **Tablet (768px – 1023px)**: 8 columns, `1.5rem` gutters, and `1.5rem` margins.
- **Mobile (< 768px)**: 4 columns, `1rem` (`16px`) gutters, and `1rem` canvas margins.

Generous vertical spacing (`space-xl` and `space-2xl`) cleanly delineates portfolio sections (Hero, Academic Profile, Tech Stack, Projects, Contact), allowing dense project details to breathe without feeling cramped.

## Elevation & Depth

Visual hierarchy avoids heavy drop shadows, instead leveraging **tonal layering**, **crisp micro-borders**, and **subtle ambient glow**:

- **Level 0 (Canvas)**: Solid `#0b0f19`. No borders or elevation.
- **Level 1 (Card & Content Blocks)**: Surface `#111827` framed with a 1px border `rgba(255, 255, 255, 0.08)`. Ambient drop shadow: `0 1px 3px rgba(0, 0, 0, 0.3)`.
- **Level 2 (Hover & Focus States)**: Surface remains `#111827`, border shifts to `rgba(59, 130, 246, 0.45)`, accompanied by a restrained blue glow: `0 8px 24px -4px rgba(29, 78, 216, 0.15)`.
- **Level 3 (Modals & Overlays)**: Surface `#1e293b` with a 1px border `rgba(255, 255, 255, 0.14)` and a deep shadow `0 20px 30px -8px rgba(0, 0, 0, 0.6)`.

## Shapes

The interface embraces a **Soft (Level 1)** geometric standard. This delivers a pragmatic, engineered aesthetic that steers clear of overly rounded consumer tech styling:

- Standard controls, text fields, skill chips, and badges: `0.25rem` (`4px`).
- Project cards, code display blocks, and hero panels (`rounded-lg`): `0.5rem` (`8px`).
- Large structural modals or framed image containers (`rounded-xl`): `0.75rem` (`12px`).

## Components

### Buttons
- **Primary**: Solid `#1d4ed8` fill, `#ffffff` text, `4px` border radius, padding `0.625rem 1.25rem`. Transitions smoothly to `#2563eb` on hover with a crisp `2px` focus ring in `#3b82f6` with `2px` offset.
- **Secondary / Outline**: Transparent fill, 1px border in `rgba(255, 255, 255, 0.15)`, `#f8fafc` text. Hover state shifts border to `#3b82f6` and text to `#60a5fa`.
- **Ghost**: Unbordered, transparent background, `#94a3b8` text, hover background `rgba(255, 255, 255, 0.05)`.

### Skill & Technology Chips
- Height: `28px`, padding `0 0.625rem`, border radius `4px`.
- Background `rgba(30, 41, 59, 0.7)`, border `1px solid rgba(255, 255, 255, 0.08)`, text `#94a3b8` in `label-sm`.
- Featured/Core competencies (e.g., PHP, MySQL, JavaScript) display a `2px` primary-blue left accent or dot indicator.

### Project Cards
- Background `#111827`, border `1px solid rgba(255, 255, 255, 0.08)`, radius `8px`, inner padding `1.5rem`.
- Features an organized metadata header (Year, Academic/Personal, Tech tags), followed by project title, short rationale, architectural bullet points, and live/GitHub link buttons.
- On hover: border color transitions to `rgba(59, 130, 246, 0.5)` with `elevation-2` ambient blue glow.

### Form Inputs
- Background `#0b0f19`, border `1px solid rgba(255, 255, 255, 0.12)`, radius `4px`, padding `0.625rem 0.875rem`.
- Placeholder text `#475569`. Focus state applies a border of `#3b82f6` and an outer glow `0 0 0 1px #3b82f6`.

### Academic / Experience List Items
- Timeline layout with a vertical `1px` spine in `rgba(255, 255, 255, 0.1)`.
- Discrete `8px` square nodes in `#1d4ed8` marking key education and development milestones.