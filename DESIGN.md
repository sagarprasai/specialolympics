---
name: Inclusion Summit
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#5d3f3e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#926e6d'
  outline-variant: '#e6bdbb'
  surface-tint: '#bf0028'
  primary: '#bb0027'
  on-primary: '#ffffff'
  primary-container: '#e51937'
  on-primary-container: '#fffcff'
  inverse-primary: '#ffb3b1'
  secondary: '#495d91'
  on-secondary: '#ffffff'
  secondary-container: '#aec2fe'
  on-secondary-container: '#3b4f82'
  tertiary: '#5d5c5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#757474'
  on-tertiary-container: '#f7feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#dae2ff'
  secondary-fixed-dim: '#b2c5ff'
  on-secondary-fixed: '#001847'
  on-secondary-fixed-variant: '#304578'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  headline-xl:
    fontFamily: Raleway
    fontSize: 56px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Raleway
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Raleway
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Raleway
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  eyebrow:
    fontFamily: Raleway
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  body-lg:
    fontFamily: Merriweather
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Merriweather
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Raleway
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
  cta:
    fontFamily: Raleway
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1.0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  gutter: 32px
  margin-desktop: 80px
  container-max-width: 1280px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The design system is anchored in the spirit of athletic excellence and radical inclusion. It balances the high-energy intensity of a global sports organization with a warm, human-centric approach tailored to the cultural landscape of Nepal. 

The aesthetic is **Corporate Modern with Editorial Flair**, characterized by expansive white space, precise grid alignments, and a confident use of the national palette. It aims to evoke a sense of pride, professionalism, and accessibility, ensuring that athletes, families, and donors alike feel a sense of belonging within a world-class sporting environment. 

Key visual principles include:
- **Heroic Scale:** Utilizing large-scale imagery and bold typography to celebrate the athletes' triumphs.
- **Architectural Clarity:** A disciplined layout that uses generous padding to prioritize legibility and focus.
- **Dynamic Energy:** Subtle diagonal accents and vibrant gradients inspired by the topography of the Himalayas to provide a contemporary edge.

## Colors

The color strategy is rooted in the "Special Olympics Red" for action and "Deep Royal Blue" for authority and trust.

- **Primary (Red):** Used exclusively for high-priority calls to action, brand identifiers, and active states.
- **Major Anchor (Navy):** Provides the structural foundation, used for secondary buttons, navigation bars, and footer backgrounds to ground the UI.
- **Text (Dark Navy):** A softened black (#1A1A1A) is used for all body and heading content to maintain high contrast while appearing more sophisticated than pure black.
- **Subtle Background (Light Grey):** Utilized for section alternates and card backgrounds to define boundaries without adding visual noise.
- **Gradients:** Use linear gradients from `primary` to a deeper crimson or `secondary` to a softer royal blue for impactful hero backgrounds or data visualizations.

## Typography

This design system pairs **Raleway** and **Merriweather** to achieve editorial elegance and optimal legibility:
- **Headlines & UI Elements (Raleway):** Raleway's sleek strokes and neo-grotesque-inspired style make headlines, eyebrows, labels, and action buttons stand out with crisp modern authority.
  - **Headlines:** Use `ExtraBold` (800) for hero sections and `Bold` (700) for standard headings with tight letter spacing for a punchy, editorial presence.
  - **Eyebrows & Labels:** Use `uppercase` with tracking set to `0.1em` in `Bold` (700) or `SemiBold` (600).
- **Body & Longform Copy (Merriweather):** Merriweather's classic appearance, sturdy serifs, and condensed letterforms ensure comfortable, fatigue-free on-screen reading.
  - **Body Copy:** Standard body text uses `Regular` (400) weight with generous `1.6` line-height. For emphasis or dense callouts, use `Bold` (700).

## Layout & Spacing

The layout philosophy follows a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 

- **Breathing Room:** This system emphasizes "generous whitespace." Section vertical padding is significantly higher than industry standards (120px) to allow each story or program to stand on its own.
- **Alignment:** Content is primarily left-aligned to mirror natural reading patterns, though section headers and hero content may be centered for impact.
- **Reflow:** On mobile, margins reduce to 24px, and section padding scales down to 64px. Multi-column card layouts collapse into a single-column vertical stack.

## Elevation & Depth

To maintain a "Premium Sports" feel, elevation is achieved through **low-contrast outlines** and **subtle ambient shadows**.

- **Cards:** Use a 1px border in `Light Grey` (#E2E8F0) paired with a very soft, diffused shadow (0px 4px 20px rgba(0, 0, 0, 0.04)). This creates a "lifted" effect without the UI feeling heavy or cluttered.
- **Tonal Layers:** High-importance sections should use the `Light Grey` background to create a secondary visual plane, separating them from the main white content areas.
- **Interactive Depth:** On hover, cards should slightly increase their shadow depth and move -4px on the Y-axis to provide tactile feedback.

## Shapes

The shape language is **Soft (0.25rem)** to reflect professionalism and precision while maintaining an approachable human feel.

- **Primary Buttons:** Use `rounded-lg` (0.5rem) to make them prominent and friendly.
- **Cards and Input Fields:** Use standard `rounded` (0.25rem) for a crisp, organized appearance.
- **Avatars/Icons:** Use full circles (`rounded-full`) for people-focused imagery and circular backgrounds behind icons to emphasize the "Inclusion" aspect through soft, repeating geometry.

## Components

### Buttons
- **Primary:** Background `Red`, Text `White`. Bold, uppercase text. Features a right-arrow icon for momentum.
- **Secondary:** Background `Transparent`, Border 2px `Navy`, Text `Navy`. Used for less urgent actions.
- **Tertiary:** Text-only with a heavy underline or trailing icon in `Navy`.

### Cards
- **Editorial Card:** Large image at the top with a `1:1` or `4:3` aspect ratio, followed by an `eyebrow`, `headline-md`, and `body-md`. 
- **Stats Card:** Centered typography featuring large numeric displays in `Navy` with `Red` labels.

### Input Fields
- **Search/Form:** 1px `Grey` border, `16px` padding. Focus state switches border to `Navy` with a 2px outer glow.

### Chips & Badges
- Used for categories (e.g., "News", "Event"). Small, uppercase labels with a light tinted background of the category's theme color (e.g., light red background with dark red text).

### Interactive Elements
- **Carousel Controls:** Large circular white buttons with `Navy` icons and soft shadows.
- **Navigation:** Top-level links in `Navy` with a `Red` bottom-border active state.