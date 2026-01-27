# Design Style Guide - Resto Danny

This document serves as a reference for the visual design language of the Resto Danny website. The design aims to be warm, welcoming, and grounded, reflecting the values of community, heritage, and food security.

## Typography

The website uses a pairing of a classic serif font for headings and a clean sans-serif for body text.

### Headings
*   **Font Family:** Playfair Display
*   **Weights:** 400 (Regular), 700 (Bold)
*   **Usage:** Main titles (H1), Section headers (H2, H3), Brand name in footer.
*   **Feel:** Elegant, traditional, human.

### Body Text
*   **Font Family:** Lato
*   **Weights:** 300 (Light), 400 (Regular), 700 (Bold)
*   **Usage:** Paragraphs, navigation links, buttons, UI elements.
*   **Feel:** Modern, legible, friendly.

## Color Palette

The color scheme relies on earthy tones ("Stone") for structure and warm accents ("Amber") to evoke food, warmth, and hospitality. (Based on Tailwind CSS default palette).

### Primary Colors (Amber)
Used for calls to action, highlights, and branding.

*   **Amber 100:** `#fef3c7` (Icon backgrounds)
*   **Amber 300:** `#fcd34d` (Accents on dark backgrounds)
*   **Amber 400:** `#fbbf24` (Icons on dark backgrounds)
*   **Amber 600:** `#d97706` (Hover states, Hero button)
*   **Amber 700:** `#b45309` (Primary Brand Color, Buttons, Links)
*   **Amber 800:** `#92400e` (Darker interaction states)
*   **Amber 900:** `#78350f` (Dark backgrounds)

### Neutral Colors (Stone)
Used for backgrounds, text, and structure to provide a warm, organic foundation.

*   **Stone 50:**  `#fafaf9` (Page background)
*   **Stone 100:** `#f5f5f4` (Section alternates, Borders)
*   **Stone 200:** `#e7e5e4` (Placeholders)
*   **Stone 400:** `#a8a29e` (Footer text, Disabled)
*   **Stone 500:** `#78716c` (Quotes, Muted text)
*   **Stone 600:** `#57534e` (Body text)
*   **Stone 800:** `#292524` (Primary text)
*   **Stone 900:** `#1c1917` (Headings, Footer background)
*   **White:** `#ffffff` (Cards, Navigation)

## UI Components

### Buttons
*   **Primary:** Amber 700 background, White text. Rounded corners (full or medium). Hover darkens to Amber 800.
*   **Secondary:** White background, Amber 700 text, Amber 700 border.
*   **Shape:** Generally rounded-full for main actions, rounded-md for smaller UI elements.

### Cards
*   **Background:** White.
*   **Border:** Stone 100 (Subtle).
*   **Shadow:** `shadow-sm` initially, `shadow-md` on hover.
*   **Radius:** `rounded-xl` (12px).

### Icons
*   **Library:** Lucide Icons.
*   **Style:** Clean lines.
*   **Presentation:** Often contained within a circle of Amber 100 with Amber 700 stroke.

## Layout & Spacing
*   **Container:** `max-w-6xl` generally used for main content width.
*   **Section Spacing:** Generous padding (`py-20` / `py-24`) to create breathing room.
*   **Grid:** Standard CSS Grid layouts (`grid-cols-1` mobile to `grid-cols-2` or `3` on desktop).

## Visual Tone
*   **Images:** Warm, inviting, human-centric. Overlays (gradients) used to ensure text readability on hero images.
*   **Atmosphere:** Community-focused, resilient, and hospitable.
