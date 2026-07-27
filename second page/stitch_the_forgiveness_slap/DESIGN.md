---
name: Heartfelt Apology
colors:
  surface: '#fff8f9'
  surface-dim: '#e1d8db'
  surface-bright: '#fff8f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f4'
  surface-container: '#f5ebee'
  surface-container-high: '#efe6e9'
  surface-container-highest: '#eae0e3'
  on-surface: '#1f1a1d'
  on-surface-variant: '#574146'
  inverse-surface: '#342f31'
  inverse-on-surface: '#f8eef1'
  outline: '#8a7176'
  outline-variant: '#ddbfc5'
  surface-tint: '#ab2c5d'
  primary: '#ab2c5d'
  on-primary: '#ffffff'
  primary-container: '#f06292'
  on-primary-container: '#5e002b'
  inverse-primary: '#ffb1c5'
  secondary: '#805062'
  on-secondary: '#ffffff'
  secondary-container: '#fec1d6'
  on-secondary-container: '#7b4c5e'
  tertiary: '#a82d68'
  on-tertiary: '#ffffff'
  tertiary-container: '#ec639e'
  on-tertiary-container: '#5c0033'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#ffb1c5'
  on-primary-fixed: '#3f001b'
  on-primary-fixed-variant: '#8b0e45'
  secondary-fixed: '#ffd9e4'
  secondary-fixed-dim: '#f2b6cb'
  on-secondary-fixed: '#330f1f'
  on-secondary-fixed-variant: '#65394b'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cc'
  on-tertiary-fixed: '#3e0020'
  on-tertiary-fixed-variant: '#890f50'
  background: '#fff8f9'
  on-background: '#1f1a1d'
  surface-variant: '#eae0e3'
typography:
  headline-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  element-gap: 12px
---

## Brand & Style
The brand personality is sincere, whimsical, and deeply personal. It aims to soften a difficult conversation with a friend through a visual language that is disarmingly sweet and intentionally "un-corporate." The emotional response should be a mix of nostalgia, warmth, and a gentle smile.

The design style is **Tactile Retro-Pop**. It utilizes the concentric heart patterns from the reference image as a recurring motif. It leans into "squishy" physical metaphors, using soft shadows and high-gloss finishes to make UI elements feel like physical stickers or vinyl decals. The aesthetic is intentionally high-energy but grounded in a soft, monochromatic pink palette to keep the message focused on affection and reconciliation.

## Colors
The palette is derived directly from the reference image’s concentric heart pattern.
- **Primary:** A vibrant "Electric Rose" (#F06292) used for calls to action and primary messaging.
- **Secondary:** A "Soft Blush" (#F8BBD0) for secondary backgrounds and layered patterns.
- **Tertiary:** A deep "Plum Wine" (#880E4F) reserved for high-contrast text to ensure legibility against light pink backgrounds.
- **Neutral:** A warm "Sugar White" (#FFF5F8) that keeps the interface feeling airy and clean.

Color should be applied in rhythmic gradients to mimic the "pulsing" heart effect seen in the reference material.

## Typography
The typography strategy pairs expressive, quirky headlines with soft, readable body text. 

**Bricolage Grotesque** is used for headlines to provide a playful, slightly off-kilter energy that feels custom and handmade. For larger display moments, tight tracking and heavy weights are encouraged to mimic the boldness of 90s sticker art.

**Plus Jakarta Sans** provides a friendly and modern counterpoint for body copy. Its rounded terminals harmonize with the heart-based iconography while ensuring the "sorry" message is easy to digest. All text should be rendered in the tertiary "Plum Wine" color rather than pure black to maintain the soft aesthetic.

## Layout & Spacing
The design system uses a **Fluid Center-Aligned** layout. Because the message is personal, content should be contained in floating "cards" or "pods" that sit centered on a backdrop of the heart pattern.

- **Mobile:** Single column with 24px side margins. Elements are stacked vertically with generous gaps to avoid a cluttered feel.
- **Desktop:** A maximum content width of 800px to keep the reading experience intimate. 
- **Rhythm:** Use an 8px base grid. Spacing between different sections of the apology should be wide (48px+) to allow the user to pause and reflect, whereas interactive elements (buttons/chips) should be tightly grouped (12px).

## Elevation & Depth
Hierarchy is achieved through **Soft Tonal Layering** and **Tactile Shadows**.

- **Surfaces:** Use high-transparency glassmorphism (white at 60% opacity with a 20px blur) for content containers. This allows the heart pattern background to peek through, creating a sense of depth without sacrificing legibility.
- **Shadows:** Avoid harsh black shadows. Use "Ambient Glows"—shadows tinted with the Primary color (#F06292) at low opacity (15-20%) and high spread (30px). This makes components appear as if they are floating gently above the heart-patterned surface.
- **Inner Depth:** Use subtle inner shadows on input fields to make them feel "pressed" into a soft surface.

## Shapes
The shape language is exclusively **Pill-shaped and Organic**. 

Sharp corners are forbidden. Every element—from buttons to the main message container—should utilize extreme corner radii to evoke a "bubble" or "heart" feel. Use `rounded-xl` (1.5rem) as the minimum for small components and `rounded-full` for buttons and decorative chips. This softness reinforces the "gentle" nature of an apology.

## Components
- **Buttons:** Large, pill-shaped, and bouncy. Use the Primary pink with a white label. Apply a slight 2px vertical offset on hover to simulate a physical button being pressed.
- **Cards:** Use the glassmorphic style described in Elevation. Borders should be a 2px solid line in Secondary pink (#F8BBD0) to give them a "sticker" edge.
- **Chips/Tags:** Small, playful indicators used for "feelings" or "moods." These should use the Secondary pink background with Tertiary text.
- **Input Fields:** Softly rounded with a thick 2px border that transitions from Secondary to Primary color when focused. 
- **Iconography:** Use "blobby" or hand-drawn style icons. Heart icons should be the primary decorative element, used as bullet points in lists or as floating background particles.
- **Progress Bars:** Designed as a "growing heart" or a smooth pink gradient filling a pill-shaped track.