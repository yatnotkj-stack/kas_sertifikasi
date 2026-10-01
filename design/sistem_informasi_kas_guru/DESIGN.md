---
name: Sistem Informasi Kas Guru
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#444651'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#002173'
  on-tertiary: '#ffffff'
  tertiary-container: '#0033a6'
  on-tertiary-container: '#92a7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b7c4ff'
  on-tertiary-fixed: '#001551'
  on-tertiary-fixed-variant: '#0039b5'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-lg:
    fontFamily: Public Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Public Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  tabular-finance-lg:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  tabular-finance-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.025em
  label-sm:
    fontFamily: Public Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an authoritative, accessible, and institutional civil-service platform tailored for Indonesian educational governance and financial management. Designed specifically for managing teacher certification funds and organizational dues (*Iuran Kas Sertifikasi Guru*), the design narrative projects absolute integrity, procedural transparency, accountability, and bureaucratic clarity.

The visual style blends modern corporate clarity with disciplined public-sector design patterns:
- **Tone:** Authoritative, dependable, orderly, and meticulously structured.
- **Visual Aesthetic:** Minimalist-institutional. The platform employs high contrast, crisp structural dividers, functional surface layering, and zero-distraction layouts to reduce cognitive burden for civil servants, school administrators, and educators.
- **Affordance & Usability:** Prioritizes tabular figures for currency accounting, legible operational status indicators, and predictable hierarchical navigation conforming to stringent accessibility benchmarks (WCAG 2.1 AA).

## Colors

The palette is engineered to communicate institutional authority, regulatory compliance, and unambiguous financial tracking:

- **Primary (`#1E3A8A`) & Tertiary Accent (`#1D4ED8`):** Deep Royal Navy conveys institutional permanence, judicial stability, and official credibility. Used for authoritative structural chrome, primary navigation bars, main action buttons, active tabs, and emphasized ledger headers.
- **Secondary Accent (`#F59E0B` / `#EAB308`):** Warm Golden Amber serves as an operational callout color, representing certified status seals, pending verifications, focal KPI card highlights, and secondary alerts without causing panic.
- **Neutral Core:** Built around crisp, clinical backgrounds (`#FFFFFF` canvas, `#F8FAFC` sub-tier panels, `#F1F5F9` row dividers) paired with high-legibility slate typography (`#0F172A` headings, `#334155` body, `#64748B` supporting labels).
- **Functional Status Indicators:**
  - *Lunas / Disetujui (Success):* Emerald Green (`#059669` fill, `#ECFDF5` background, `#A7F3D0` border).
  - *Dalam Verifikasi (Informational):* Royal Azure (`#2563EB` fill, `#EFF6FF` background, `#BFDBFE` border).
  - *Menunggu / Pending (Warning):* Warm Amber (`#D97706` fill, `#FFFBEB` background, `#FDE68A` border).
  - *Ditolak / Bermasalah (Critical):* Crimson Red (`#DC2626` fill, `#FEF2F2` background, `#FECACA` border).

## Typography

The design system standardizes exclusively on **Public Sans**, an open, neutral, and structurally disciplined typeface developed specifically for administrative dashboards, official state publications, and dense tabular data.

### Typographic Rules
- **Tabular Figures (`tnum`):** All financial summaries, ledger items, Indonesian Rupiah values (`Rp 1.250.000`), NIP/NIK identification numbers, and serial codes must force the OpenType tabular figure variant (`font-feature-settings: "tnum" 1`) to guarantee perfect vertical numerical alignment.
- **Hierarchy & Case:** Form section headers, official table titles, and metric categories utilize sentence case with selective uppercase badge trackers (`LUNAS`, `VERIFIKASI`). 
- **Readability & Scaling:** Heading levels step down gracefully across mobile devices (`display-lg-mobile`) ensuring dashboard cards do not truncate crucial fund balances on compact displays.

## Layout & Spacing

The layout is grounded in a disciplined 8-point baseline spatial system:

- **Desktop (1024px and above):** Utilizes a structured 12-column layout with a 280px persistent institutional sidebar, 24px (`gutter`) column spacing, and 32px (`margin`) outer canvas margins. Tables, balance sheets, and audit trails occupy maximum horizontal width up to a controlled 1440px canvas limit.
- **Tablet (768px - 1023px):** Adapts to an 8-column layout. The primary navigation collapses into an off-canvas drawer or consolidated top bar. Gutters compress to 16px (`gutter-sm`) with 24px margins.
- **Mobile (< 768px):** Reflows into a single 4-column flow with 16px outer margins (`margin-sm`). Multi-column tables collapse into vertical structured records or horizontally scrollable containers with frozen first columns.
- **Interior Layout Rhythm:** Component padding operates in strict increments: `space-xs` (4px) for tag insets, `space-sm` (8px) for table cell vertical bounds and input padding, `space-md` (16px) for module card interiors, and `space-xl` (32px) separating primary fiscal sections.

## Elevation & Depth

To avoid visual ambiguity, the elevation strategy favors **structural outlines and disciplined surface tiers** over dramatic shadows:

1. **Surface Tiers (Flat & Structural):**
   - **Canvas Layer (`#F8FAFC`):** Base workspace background.
   - **Card & Table Layer (`#FFFFFF`):** High-contrast interactive foreground bounded by 1px solid `#E2E8F0` borders.
   - **Muted Table Headers & Inset Wells (`#F1F5F9`):** Grounded containers for totals, filter toolbars, and aggregate calculation footers.
2. **Elevations:**
   - **Level 0 (Flat):** All table structures, form inputs, inline metrics, and status panels sit strictly at level 0, defined by `1px solid #E2E8F0`.
   - **Level 1 (Hover & Dropdowns):** `0 2px 4px -1px rgba(15, 23, 42, 0.06), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`. Applied to active dropdown menus, contextual filters, and button hover states.
   - **Level 2 (Modals & Verification Sheets):** `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`. Restrained and crisp, framed by an exterior `1px solid #CBD5E1` border to preserve official legibility.

## Shapes

The design system enforces a **Soft (`1`)** shape language, conveying precision, institutional discipline, and efficient spatial usage:

- **Corner Radii Hierarchy:**
  - Base interactive controls (Buttons, Text Inputs, Select Triggers): `0.25rem` (4px).
  - Status badges, verification tags, and pills: `0.25rem` (4px) or full containment capsules for small indicator chips.
  - Data containers, ledger cards, KPI metric blocks, and modals: `rounded-lg` (`0.5rem` / 8px).
  - Toast notifications and system banners: `0.375rem` (6px).
- **Proportional Economy:** No hyper-rounded or playful shapes are used. Corner treatments remain formal, crisp, and aligned with standard governmental filing formats.

## Components

### Buttons
- **Primary Action (Pengajuan, Simpan Data):** Solid Royal Navy (`#1E3A8A`) background, white text, 4px border radius, 40px height for desktop. On hover, background shifts to `#1D4ED8`. Focus state displays a 2px offset ring in `#93C5FD`.
- **Secondary Action (Ekspor Excel/PDF, Filter):** Crisp white background with a 1px border in `#CBD5E1`, text color in `#1E293B`. Hover shifts to `#F8FAFC`.
- **Accent Highlight (Verifikasi Sertifikasi):** Warm Golden Amber (`#F59E0B`) background with white bold text, reserved exclusively for validation actions and certificate clearance tasks.

### Status Badges (Status Pembayaran & Berkas)
- Rendered in 4px radius chips with 11px uppercase bold Public Sans, containing a 6px status dot:
  - **Lunas / Disetujui:** Background `#ECFDF5`, text `#065F46`, border `1px solid #A7F3D0`.
  - **Dalam Verifikasi:** Background `#EFF6FF`, text `#1E40AF`, border `1px solid #BFDBFE`.
  - **Menunggu Pembayaran (Pending):** Background `#FFFBEB`, text `#92400E`, border `1px solid #FDE68A`.
  - **Ditolak / Belum Valid:** Background `#FEF2F2`, text `#991B1B`, border `1px solid #FECACA`.

### Financial Data Tables
- Header row styled in `#F8FAFC` background with subtle bottom rule (`1px solid #E2E8F0`), label font in 12px uppercase medium slate (`#475569`).
- Row zebra striping: alternating `#FFFFFF` and `#FAFAFA`. Row hover effect: `#F1F5F9`.
- Monospaced tabular alignment: Currency (`Rp`) values align strictly right; status badges and reference IDs center-align; teacher names and descriptions align left.
- Sticky footer calculation row for total aggregate receipts (`Total Kas Terkumpul`) highlighted in `#F8FAFC` with bold 14px tabular numbers.

### KPI & Metric Summary Cards
- White background with `1px solid #E2E8F0` border and `0.5rem` radius.
- Includes a 3px vertical accent indicator line on the left border: Primary Blue (`#1E3A8A`) for general balances, Golden Yellow (`#F59E0B`) for pending approvals, and Green (`#059669`) for verified teacher quotas.
- Displays metric title in 12px uppercase slate (`#64748B`), balance figure in 24px bold Public Sans (`tabular-finance-lg`), and subtext showing period comparisons.

### Input Fields & Search Controls
- 38px height, 1px solid border in `#CBD5E1`, white background, 4px radius.
- Inactive placeholder in `#94A3B8`; active focus triggers a crisp 1px `#1E3A8A` border accompanied by an ambient `#DBEAFE` halo.
- Numeric currency fields include an integrated left-anchored prefix badge (`Rp`) in `#F1F5F9` with a subtle divider.

### Checkboxes & Radios
- Square 16px boxes with 2px radius and 1px `#CBD5E1` border.
- Selected state turns solid `#1E3A8A` with a crisp white institutional checkmark. Focus states maintain keyboard visibility rings conforming to standard civil-service accessibility mandates.