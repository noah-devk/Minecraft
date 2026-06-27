---
name: Overworld Launcher
colors:
  surface: '#101510'
  surface-dim: '#101510'
  surface-bright: '#363a34'
  surface-container-lowest: '#0b0f0b'
  surface-container-low: '#181d18'
  surface-container: '#1c211b'
  surface-container-high: '#272b26'
  surface-container-highest: '#313630'
  on-surface: '#e0e4db'
  on-surface-variant: '#bfc9bb'
  inverse-surface: '#e0e4db'
  inverse-on-surface: '#2d322c'
  outline: '#8a9387'
  outline-variant: '#40493f'
  surface-tint: '#8ad88e'
  primary: '#8ad88e'
  on-primary: '#003911'
  primary-container: '#55a15d'
  on-primary-container: '#00320d'
  inverse-primary: '#1f6c2f'
  secondary: '#ebbcac'
  on-secondary: '#46291e'
  secondary-container: '#603f33'
  on-secondary-container: '#d8ab9b'
  tertiary: '#ffb1c4'
  on-tertiary: '#5e112f'
  tertiary-container: '#d6718f'
  on-tertiary-container: '#550828'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a6f5a8'
  primary-fixed-dim: '#8ad88e'
  on-primary-fixed: '#002107'
  on-primary-fixed-variant: '#00531b'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ebbcac'
  on-secondary-fixed: '#2e150b'
  on-secondary-fixed-variant: '#603f33'
  tertiary-fixed: '#ffd9e1'
  tertiary-fixed-dim: '#ffb1c4'
  on-tertiary-fixed: '#3f001a'
  on-tertiary-fixed-variant: '#7b2945'
  background: '#101510'
  on-background: '#e0e4db'
  surface-variant: '#313630'
  deep-forest: '#1B3022'
  dirt-darker: '#4D342C'
  grass-vibrant: '#54B061'
  surface-charcoal: '#121212'
  xp-green: '#C6FF00'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button-text:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
---

## Brand & Style

This design system draws inspiration from official gaming ecosystems, merging the rugged, blocky charm of sandbox construction with the sleek utility of a high-end application launcher. The aesthetic is **Modern Gamer-Centric**, prioritizing high-contrast legibility against deep, textured backgrounds.

The visual narrative is built on the tension between organic "dirt and forest" elements and sharp, digital precision. It utilizes **Minimalism** for layout structures—to ensure the interface feels professional—while incorporating **Tactile** textures and micro-interactions that mirror the game's physical world. The atmosphere is immersive, authoritative, and sophisticated, avoiding "childish" tropes in favor of a "Pro-Tools" feel for creators and players.

## Colors

The palette is anchored in a **Dark Mode** foundation to reduce eye strain and emphasize vibrant game assets. 

- **Primary (Forest Green):** Used for primary CTAs and active states. It represents growth and the iconic "grass block" surface.
- **Secondary (Dirt Brown):** Utilized for structural accents and depth. It provides a grounded, earthy warmth to the technical UI.
- **Surface Strategy:** Backgrounds utilize `deep-forest` for large areas, while containers use `dirt-darker` or `surface-charcoal` to create a tiered visual hierarchy.
- **High-Contrast Accents:** `xp-green` is reserved for success states, progress bars, and critical highlights to draw the eye immediately.

## Typography

This design system employs a tiered typography strategy to balance theme and utility:

1.  **Headlines (Space Grotesk):** A geometric sans with a technical, "blocky" feel that echoes pixel-grid construction without sacrificing modern readability.
2.  **Body (Hanken Grotesk):** A clean, contemporary sans-serif used for all long-form content and descriptions to ensure a professional, "launcher-like" experience.
3.  **Technical Labels (JetBrains Mono):** Used for metadata, version numbers, and secondary navigation to reinforce the "coder/gamer" aesthetic.

All headlines should favor tighter letter-spacing to appear impactful and architectural.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop screens to mimic the focused experience of a desktop application. 

- **Grid:** A 12-column system with a 24px gutter. Content is centered within a 1280px maximum width.
- **Rhythm:** Spacing follows an 8px linear scale. Large sections are separated by 80px (`10x`) to allow the high-quality textures to "breathe."
- **Mobile Adaption:** On mobile, the grid collapses to a single column with 16px side margins. Typography scales down (e.g., `display-lg` to `display-lg-mobile`) to maintain hierarchy without horizontal overflow.
- **Launcher Feel:** Vertical centering is preferred for hero sections and call-to-action modules to simulate a standalone app dashboard.

## Elevation & Depth

Depth is achieved through **Tonal Layers** and subtle **Ambient Shadows** rather than extreme blur.

- **Surface Tiers:** Backgrounds are the darkest (`deep-forest`). Cards and containers use `dirt-darker` with a subtle 1px inner border of a lighter shade to simulate "beveled" block edges.
- **Pixel Shadows:** Shadows should be crisp and slightly offset (e.g., `4px 4px 0px rgba(0,0,0,0.3)`) rather than soft and diffused, nodding to pixel-art lighting.
- **Glassmorphism:** Use sparingly for overlays (modals or navigation bars) with a high-density blur (20px+) and a 10% opacity white tint to suggest a "crystal" or "ice" material.

## Shapes

To maintain the block-based DNA of the theme, the design system utilizes **Soft (0.25rem)** roundedness. 

- **Standard Elements:** Buttons and small input fields use a 4px (0.25rem) radius. This provides a "machined" look that is cleaner than raw 0px edges.
- **Large Containers:** Cards and modal containers may use the `rounded-lg` (8px) setting to create a clear distinction from the background.
- **Strictness:** Avoid pill-shapes or high-radius circles. Icons should be encased in square or slightly rounded-square housing.

## Components

### Buttons
Primary buttons use the `primary-color` with a "pressed" animation that shifts the element 2px down and right. They feature all-caps `button-text` and a subtle pixelated texture overlay at 5% opacity.

### Cards
Cards are constructed with a `dirt-darker` background and a 1px solid border using a lighter brown shade. Headers within cards should have a distinct background-color block to separate content.

### Inputs
Input fields use a near-black background with a `primary-color` focus ring. The cursor should be a non-blinking block to reinforce the retro-tech aesthetic.

### Chips & Tags
Use `jetbrainsMono` for chip text. These should have 0px border-radius and a solid background color (e.g., `secondary_color_hex`) to act as "labels" on game versions or server statuses.

### Progress Bars
Utilize the `xp-green` for the fill. The track should be a dark neutral with a slight inner shadow to indicate depth.