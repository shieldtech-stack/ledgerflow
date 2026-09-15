---
name: Modern FinTech Ledger
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9fa'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3ff'
  surface-container: '#ebedff'
  surface-container-high: '#e3e7ff'
  surface-container-highest: '#dbe1ff'
  on-surface: '#131a33'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#282f49'
  inverse-on-surface: '#eff0ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#545d7c'
  on-secondary: '#ffffff'
  secondary-container: '#d0d9fd'
  on-secondary-container: '#555e7d'
  tertiary: '#006c4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#3eb686'
  on-tertiary-container: '#00422c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#bdc5e9'
  on-secondary-fixed: '#111a36'
  on-secondary-fixed-variant: '#3d4664'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#faf8ff'
  on-background: '#131a33'
  surface-variant: '#dbe1ff'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-numeric-lg:
    fontFamily: JetBrains Mono
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.02em
  label-numeric-md:
    fontFamily: JetBrains Mono
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-numeric-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1rem
  margin-sm: 0.75rem
  margin-lg: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

The design system establishes a high-trust, precision-driven FinTech aesthetic engineered specifically for independent operators, contractors, and modern businesses issuing invoices on mobile. 

The emotional tone balances absolute financial integrity with crisp, effortless execution. It departs from sterile banking conventions by pairing institutional deep slate tones with energetic emerald accents—evoking liquidity, verified accuracy, and modern momentum.

The design movement fuses **Minimalism** and **Tactile Precision**:
- High-contrast visual structure anchored by crisp micro-borders (1px keylines) rather than heavy drop shadows.
- Structural layout integrity where financial numbers, status tags, and currency symbols maintain rigorous optical balance.
- Utilitarian efficiency designed for swift thumb-reach capture, generation, and multi-channel receipt delivery.

## Colors

The palette is tuned for high-legibility transactional surfaces and quick-glance status recognition.

### Palette Roles
- **Primary (`#10B981`) & Tertiary (`#059669`)**: Emerald green signals confirmation, completed revenue, active creation triggers, and primary actions. `#059669` is reserved for pressed button states, focused borders, and high-emphasis textual indicators.
- **Secondary (`#1C2541`) & Neutral (`#0B132B`)**: Deep navy anchors structural chrome, dark hero banners, bottom sheets, and high-impact metric cards.
- **Surfaces**: Canvas background lives at `#F8FAFC`. Card surfaces and nested panels sit on pure `#FFFFFF`, bounded by structural slate lines (`#E2E8F0`).
- **Text Hierarchy**:
  - `Text Primary`: `#0F172A` (Invoicing totals, counterparty titles, key values).
  - `Text Secondary`: `#475569` (Line-item labels, tax breakdowns, timestamps).
  - `Text Muted`: `#94A3B8` (Placeholders, inactive dates, unit descriptors).

### Financial Status Tokens
- **Paid**: Emerald surface (`#ECFDF5`), emerald border (`#A7F3D0`), text (`#047857`).
- **Pending**: Amber surface (`#FFFBEB`), amber border (`#FDE68A`), text (`#B45309`).
- **Overdue**: Rose surface (`#FFF1F2`), rose border (`#FECDD3`), text (`#BE123C`).
- **Draft**: Slate surface (`#F1F5F9`), slate border (`#CBD5E1`), text (`#475569`).

## Typography

The type system blends contemporary grotesque efficiency (**Hanken Grotesk**) with technical monospaced precision (**JetBrains Mono**).

- **Hanken Grotesk** powers the application framework, navigation, counterparty identifiers, and section headers. Its tight aperture and clean geometric cuts maintain exceptional readability in dense accounting views.
- **JetBrains Mono** is deployed strictly for tabular financial figures, invoice IDs (`#INV-2024-001`), tax rates, currency symbols, and unit measurements. This prevents horizontal digit jitter during real-time total recalculations.
- **Label Caps** are always transformed to uppercase to anchor micro-metric headers (e.g., `DUE DATE`, `BALANCE OUTSTANDING`, `VAT NUMBER`).

## Layout & Spacing

The layout is built for single-handed mobile usage within portrait constraints:
- **Base Grid**: A 4-column fluid layout on phones with `16px` (`1rem`) outer screen margins and `16px` gutters.
- **Form Factor Guardrails**: Content never stretches indefinitely; it caps at `480px` centered width if rendered on wider viewports or tablets.
- **Vertical Spacing Rhythm**: All form groups and line-item lists stack along an `8px` modular grid. `space-xs` (4px) isolates grouped input descriptions; `space-sm` (8px) separates paired labels and fields; `space-xl` (24px) segments logical document blocks (Payee, Line Items, Total Summary).
- **Safe Interaction Zone**: Persistent summary footers and primary action buttons stick to the viewport bottom with safe-area insets (`padding-bottom: max(1rem, env(safe-area-inset-bottom))`).

## Elevation & Depth

Visual hierarchy is maintained through crisp tonal layering and subtle, high-performance ambient shading rather than deep blurs.

- **Level 0 (Canvas Base)**: `#F8FAFC`. Zero elevation, pure background canvas.
- **Level 1 (Card & Content Blocks)**: `#FFFFFF` surface accompanied by a 1px solid structural border (`#E2E8F0`) and an ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Level 2 (Active Cards & Floating Metrics)**: Raised states, preview cards, and active line item editing rows. Uses `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)` over a 1px `#CBD5E1` border.
- **Level 3 (Modal Sheets & Context Menus)**: Slide-up drawers, bottom action sheets, and tax selection pickers. Elevation: `0 20px 25px -5px rgba(11, 19, 43, 0.12), 0 8px 10px -6px rgba(11, 19, 43, 0.08)`.
- **Dark Surface Contrast (Hero Summary Tile)**: A specialized inverted card (`#0B132B` background with `#1C2541` internal border) creates an authoritative focal point for gross unpaid balances and quick billing stats.

## Shapes

The design uses a coordinated geometric curve schema:
- **Cards & Primary Modules**: Strict `16px` corner radius (`rounded-lg` relative to scale), providing a friendly yet engineered touch profile.
- **Buttons & Text Fields**: `10px` to `12px` corner radius for immediate visual cue as interactive targets.
- **Badges & Chips**: Fully pill-shaped (`9999px` radius) to visually differentiate status meta-information from rectangular content fields.
- **Divider Keylines**: Always `1px` crisp boundaries rendered without rounding, maintaining structural precision.

## Components

### Buttons
- **Primary ("Generate Invoice", "Send Receipt")**: Emerald base (`#10B981`), white text (`#FFFFFF`), `12px` radius, `48px` minimum height for thumb precision. Active state drops to `#059669` with a subtle `transform: scale(0.98)` spring.
- **Secondary**: Deep slate surface (`#1C2541`), white text (`#FFFFFF`), for structural actions like "Add Line Item".
- **Ghost / Outlined**: 1px border (`#E2E8F0`), text primary (`#0F172A`), background transparent; shifts to `#F1F5F9` on touch.

### Input Fields (Amounts, Items, Quantities)
- Background `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `10px`, height `46px`, padding horizontal `14px`.
- Focused state: border color moves to `#10B981` with an outer ring `3px rgba(16, 185, 129, 0.15)`.
- Monospaced numeric inputs feature right-aligned prefixes/suffixes (`$`, `EUR`, `%`) anchored in slate muted (`#94A3B8`).

### Status Badges
- Pill layout with `4px` top/bottom and `10px` lateral padding.
- Displays a `6px` solid status dot directly adjacent to `label-caps` typography:
  - **Paid**: `#10B981` dot on `#ECFDF5` background.
  - **Pending**: `#F59E0B` dot on `#FFFBEB` background.
  - **Overdue**: `#EF4444` dot on `#FFF1F2` background.
  - **Draft**: `#94A3B8` dot on `#F1F5F9` background.

### Metric Chips & Selectors
- Compact horizontal pills with `#F1F5F9` neutral surface.
- Active toggle swaps to `#0B132B` background with pure white text and crisp numeric display.

### Invoice Line-Item Cards
- Pure white background, `16px` radius, `1px solid #E2E8F0` border.
- Layout splits into left-hand service/product title and unit breakdown (`body-md`), with right-hand monospaced price calculation (`label-numeric-md`).
- Left-swipe reveals swift contextual actions (Duplicate, Delete) styled in `#0B132B` and `#EF4444`.

### Dynamic Totals Breakdown
- Anchored card featuring subtle dashed dividers between Subtotal, Tax (VAT/GST), and Discounts.
- Final Due Amount renders in `display-lg` (`JetBrains Mono`), emphasized in `#0F172A` with an accompanying primary emerald payment trigger button.