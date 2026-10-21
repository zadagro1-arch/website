---
name: Agri-Vet Modern
colors:
  surface: '#f4fbf6'
  surface-dim: '#d4dcd7'
  surface-bright: '#f4fbf6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef5f0'
  surface-container: '#e8f0ea'
  surface-container-high: '#e3eae5'
  surface-container-highest: '#dde4df'
  on-surface: '#161d1a'
  on-surface-variant: '#414845'
  inverse-surface: '#2b322f'
  inverse-on-surface: '#ebf2ed'
  outline: '#727975'
  outline-variant: '#c1c8c4'
  surface-tint: '#47645b'
  primary: '#04221b'
  on-primary: '#ffffff'
  primary-container: '#1b3830'
  on-primary-container: '#83a297'
  inverse-primary: '#adcdc2'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#fdbf13'
  on-secondary-container: '#6c5000'
  tertiary: '#002319'
  on-tertiary: '#ffffff'
  tertiary-container: '#003b2b'
  on-tertiary-container: '#6ba78f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c9eade'
  primary-fixed-dim: '#adcdc2'
  on-primary-fixed: '#022019'
  on-primary-fixed-variant: '#2f4c44'
  secondary-fixed: '#ffdf9f'
  secondary-fixed-dim: '#fabd0d'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#b1f0d5'
  tertiary-fixed-dim: '#95d3ba'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#0d513d'
  background: '#f4fbf6'
  on-background: '#161d1a'
  surface-variant: '#dde4df'
typography:
  headline-xl:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
  headline-xl-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system embodies the operational vitality, institutional reliability, and grounded agricultural heritage of animal husbandry, poultry production, and certified veterinary distribution in Upper Egypt. The aesthetic balances agricultural earthiness with clean pharmaceutical precision.

### Design Movement & Aesthetic
The visual direction fuses **Modern Corporate** clarity with **Natural Tactility**:
- **Structured Precision:** High-contrast data presentation, clear status indicators for feeds and veterinary medication batches, and unambiguous hierarchy.
- **Organic Warmth:** Grounded deep botanical greens paired with sun-warmed grain yellows, avoiding sterile clinic tropes in favor of fertile, resilient growth.
- **RTL-First Ergonomics:** Engineered natively for Right-to-Left (Arabic) mobile consumption, accounting for single-thumb field navigation across farms, distribution depots, and veterinary clinics.

## Colors

The color palette directly references the visual identity: deep pine green reflecting life and certified science, paired with vibrant solar yellow signifying grain, poultry vitality, and high-energy feeds.

### Palette Roles
- **Primary (`#1B3830`):** Dark Pine Forest. Forms the primary brand anchor used for headers, primary action buttons, key banners, and high-emphasis navigation surfaces.
- **Secondary (`#F5B800`):** Vivid Solar Amber/Yellow. Functions as the high-visibility accent for call-to-actions, cart badges, promotion tags, batch alerts, and focal interactive states.
- **Tertiary (`#2E6B56`):** Balanced Meadow Green. Serves as supporting tone for success chips, verified pharmacy badges, stock availability tags, and active secondary tabs.
- **Neutral Dark (`#1F2623`):** Charcoal Moss. Primary text and iconography color, offering softer contrast than absolute black while maintaining contrast ratios above WCAG AAA standards.
- **Neutral Light & Surfaces:** Crisp white (`#FFFFFF`) card containers resting over subtle warm off-white canvas surfaces (`#F7F8F6` and `#EEF1ED`).

## Typography

The typography system relies on **IBM Plex Sans** (with its dedicated Arabic support), providing an architectural, structured, and legible grotesque tailored to commercial enterprise and inventory management.

### Typography Rules
- **Arabic Readability:** Generous line heights (`lineHeight: 1.5` to `1.6`) ensure diacritics and complex Arabic ligatures render cleanly without vertical clipping.
- **RTL Alignment:** Default alignment is right-aligned (`text-align: right`). Numerical values, batch numbers, dosage specs, and currency tags (`EGP / ج.م`) use tabular figure spacing for vertical alignment in invoices and price lists.
- **Visual Weight:** Titles utilize Semibold (600) and Bold (700) to balance against dark forest backgrounds and golden accents.

## Layout & Spacing

The layout model prioritizes handheld mobile devices and field tablet interfaces used by veterinarians, sales reps, and farm managers across Upper Egypt.

### Layout Principles
- **Grid Architecture:** 4-column layout on mobile devices with `16px` (`1rem`) horizontal page margins and `16px` gutters. Expands to 8 columns on tablet devices (`margin: 1.5rem`) and 12 columns on desktop management consoles (`margin: 2rem`).
- **Thumb Zone Safety:** High-frequency actions (cart additions, emergency vet consults, catalog filters) are pinned to bottom navigation rails and persistent floating action bars.
- **Content Rhythms:** Vertical spacing adheres strictly to a 4px/8px scale, using `space-xs` (4px) for micro-labels, `space-md` (16px) between product cards, and `space-xl` (36px) between thematic inventory sections (e.g., Poultry Feeds vs. Cattle Antibiotics).

## Elevation & Depth

Visual hierarchy uses clean tonal stacking and subtle ambient shadows to avoid cluttered interfaces under high sunlight conditions.

### Depth Mechanics
- **Canvas Base:** `#F7F8F6` creates a soft, eye-friendly backdrop reducing glare in direct outdoor sunlight.
- **Surface Level 1 (Cards, Product Tiles):** Solid `#FFFFFF` with a diffuse, low-contrast shadow: `0 2px 8px -2px rgba(27, 56, 48, 0.08)`. The shadow has a slight primary tint (`#1B3830`) rather than pure gray.
- **Surface Level 2 (Floating Bars, Modals, Action Sheets):** `#FFFFFF` elevated with `0 8px 24px -4px rgba(27, 56, 48, 0.14)`.
- **Borders & Dividers:** Surfaces employ subtle 1px low-contrast borders (`#E2E7E4`) rather than heavy stroke lines, giving components crisp definition against the pale gray-green canvas.

## Shapes

The shape system adopts a balanced **Rounded** (`0.5rem` / `8px` base) geometry, reflecting the organic, rounded pill motifs found directly within the brand logomark.

### Corner Curvature Scale
- **Small Elements (Inputs, Badges, Micro-chips):** `8px` (`0.5rem`) radius for clean containment.
- **Cards & Category Panels (`rounded-lg`):** `16px` (`1rem`) radius, matching modern mobile application surfaces.
- **Bottom Sheets & Drawers (`rounded-xl`):** `24px` (`1.5rem`) on top-leading and top-trailing corners.
- **Pills & Status Indicators:** Fully rounded (`rounded-full` / `9999px`) for numeric badge counts, stock tags, and pill-shaped icon backdrops mimicking veterinary capsules.

## Components

### Buttons
- **Primary Button:** Solid Forest Green (`#1B3830`) with crisp white Arabic text and optional leading RTL icon. Height: `48px` (minimum touch target). Active/press state darkens to `#132722`.
- **Accent/Action Button:** Vibrant Golden Yellow (`#F5B800`) with Deep Pine text (`#1B3830`), reserved for commercial conversion points (e.g., "أضف إلى السلة", "طلب تسعيرة فورية").
- **Secondary Button:** White surface with 1.5px border in `#1B3830` and text in `#1B3830`.
- **Ghost/Tertiary:** No background, `#1B3830` typography, used for view-all links and dismissive actions.

### Cards & Catalog Items
- **Product Card:** Elevated white surface (`#FFFFFF`) with `16px` radius and `1px` subtle outline (`#E2E7E4`). Features a designated top badge for category categorization (e.g., "أعلاف تسمين", "تحصينات داجنة", "مكملات غذائية"), product thumbnail, dual unit pricing (per ton / per sack / per bottle), and direct quick-add stepper.
- **Metric/KPI Card:** Forest Green header tile with yellow high-contrast metrics for farm account dashboards (e.g., credit limits, pending deliveries, order status).

### Input Fields & Controls
- **Text Inputs & Search:** `48px` height with `8px` radius. Neutral surface (`#FFFFFF`), border `#D2D9D5`, focused border `#1B3830` with `3px` focus ring in `rgba(245, 184, 0, 0.25)`. Search bars feature RTL search icons positioned on the right and barcode/filter triggers on the left.
- **Checkboxes & Radios:** `20px` touch targets. Unchecked: `1.5px` border in `#A4B2AB`. Checked: Primary Forest Green fill with white tick mark.
- **Chips & Filter Pills:** Segmented feed categories (دواجن, أبقار, أغنام, خيول) styled in pill containers (`rounded-full`). Inactive: `#FFFFFF` with `#E2E7E4` border. Active: `#1B3830` fill with white text or `#F5B800` accent dot.

### Specialized Veterinary & Distribution UI
- **Batch & Expiry Pill:** Compact label with clear color-coded statuses (Green: متوفر وجاهز للشحن, Amber: كمية محدودة بالمستودع, Red: يحتاج حجز مسبق).
- **RTL Navigation Bar:** Top app bar featuring the brand's white/yellow mark, back arrow pointing eastward (towards the right), and warehouse location picker badge.