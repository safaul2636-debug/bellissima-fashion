---
name: Bellissima Fashion Design System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1d0e'
  on-tertiary-container: '#848570'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e4cc'
  tertiary-fixed-dim: '#c8c8b0'
  on-tertiary-fixed: '#1b1d0e'
  on-tertiary-fixed-variant: '#474836'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is anchored in high-end editorial aesthetics, blending **Minimalism** with **Modern Typography**. It targets a discerning audience that values quiet luxury, timelessness, and sophistication. The interface should feel like a premium digital gallery—spacious, calm, and deliberate.

The visual narrative is driven by:
- **Generous Whitespace:** Utilizing negative space to elevate product imagery.
- **Editorial Balance:** High-contrast typography paired with soft, tonal backgrounds.
- **Subtle Tactility:** Using soft shadows and gold accents to create a sense of physical quality without clutter.

## Colors

The palette is a curated selection of "Evergreen Neutrals" designed to showcase fashion photography without color interference.

- **Primary (#1A1A1A):** Used for core text, iconography, and high-impact UI elements. It provides the "ink" for the editorial feel.
- **Secondary (#D4AF37):** Soft Gold is reserved for micro-interactions, active states, and premium call-to-actions. Use sparingly to maintain its value.
- **Tertiary (#F5F5DC):** Beige serves as a sophisticated alternative to pure white for section backgrounds and secondary containers, adding warmth.
- **Neutral (#FFFFFF):** The base for the canvas, providing the high-key minimalist look.

## Typography

This design system employs a "Traditional-meets-Technical" pairing. **Playfair Display** provides an authoritative, fashion-forward voice for headlines, while **Inter** ensures maximum legibility for functional data and body text.

- **Headlines:** Always use Playfair Display. For large displays, use tighter letter spacing to emphasize the high-contrast serifs.
- **Body:** Inter is used for all descriptive text. Maintain a line height of at least 1.5x for readability.
- **Labels:** Use uppercase Inter with increased letter spacing for category labels and navigational tags to create an organized, architectural feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve editorial compositions, transitioning to a **Fluid Grid** on mobile devices.

- **Desktop (1440px+):** 12-column grid with 64px side margins. Gutters are kept wide (24px) to allow elements to breathe.
- **Tablet (768px - 1024px):** 8-column grid with 32px side margins.
- **Mobile (<768px):** 4-column grid with 16px side margins. 

Spacing between sections should be aggressive (96px or 128px) to reinforce the minimalist brand positioning.

## Elevation & Depth

Hierarchy is achieved primarily through **Tonal Layering** and **Ambient Shadows**.

- **Level 0 (Base):** White (#FFFFFF) or Beige (#F5F5DC) surfaces.
- **Level 1 (Cards):** Subtle white surfaces over beige backgrounds with a very soft shadow (0px 4px 20px, 4% Black opacity). 
- **Level 2 (Overlays/Modals):** Pure white with a more defined but still soft shadow (0px 12px 40px, 8% Black opacity) and a 1px Soft Gold (#D4AF37) border at 20% opacity.
- **Backdrop:** Use a 4px background blur for modals to maintain the "Glassmorphism" hint without losing the clean aesthetic.

## Shapes

To balance the sharp serifs of the typography, the UI uses **Rounded** geometry. 

- **Primary Elements:** 0.75rem (12px) radius for product cards, input fields, and buttons.
- **Large Containers:** 1.5rem (24px) radius for promotional banners and modals.
- **Icons:** Use a 2px stroke weight with rounded caps to match the UI's softness.

## Components

### Buttons
- **Primary:** Black background, White text, 12px border-radius. On hover, a 2px bottom border in Soft Gold appears.
- **Secondary:** Transparent background, 1px Black border, Black text.
- **Tertiary (Ghost):** Soft Gold text, no border. Used for "View Details" or "Read More."

### Product Cards
- Image-first design with a 12px corner radius.
- Metadata (Name, Price) is left-aligned using Inter 14px.
- Subtle "Soft Gold" tag for "New Arrival" or "Limited Edition" in the `label-caps` style.

### Input Fields
- Underlined style or subtle 1px border (#E0E0E0).
- Focus state: Border color changes to Soft Gold (#D4AF37).
- Floating labels using the `label-caps` typography level.

### Navigation
- Sticky top header with a translucent background blur.
- Centered logo using `headline-md`.
- Navigation links in `label-caps` with a 24px horizontal gap.