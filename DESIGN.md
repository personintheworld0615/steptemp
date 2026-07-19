---
name: STEP LEO Club Design System
description: Warm and welcoming brand design system for youth volunteers and partners.
colors:
  primary: "#78d5ef"
  primary-dark: "#2c3e50"
  accent-gold: "#ffd700"
  neutral-dark: "#343a40"
  neutral-light: "#f8f9fa"
  white: "#ffffff"
typography:
  display:
    fontFamily: "Work Sans, -apple-system, sans-serif"
    fontSize: "3.5rem"
    fontWeight: 700
    lineHeight: 1.2
  body:
    fontFamily: "Work Sans, -apple-system, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  sm: "4px"
  md: "8px"
  lg: "10px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "24px"
components:
  card:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: "24px"
  button:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.sm}"
    padding: "10px 20px"
---

# Design System

## Overview
This design system defines the visual principles, components, and design tokens for the STEP LEO Club website. The primary target audience consists of young students (elementary to college) seeking volunteering opportunities, and their parents. The design focuses on being warm, dedicated, and welcoming, avoiding cold corporate structures or messy layouts.

## Colors
The color palette balances bright welcoming accents with deep, trust-inspiring dark neutrals:
- **Primary Color (`#78d5ef`)**: A warm sky blue that serves as the dominant active tone for links, hero highlights, and positive branding.
- **Accent Gold (`#ffd700`)**: Used strategically on headings, underlines, and counting numbers to draw attention to achievements and add warm energy.
- **Neutral Dark (`#343a40`)**: Used for text readability and deep backgrounds to provide structure and credibility.
- **Neutral Light (`#f8f9fa`)**: A soft off-white background color used on alternative sections to reduce eye strain.

## Typography
- **Headings**: Set in *Work Sans* with a heavy weight (700) and tight line height (1.2) for a friendly, bold look.
- **Body Text**: Set in *Work Sans* with regular weight (400) and spacious line height (1.5) to keep descriptions legible and accessible.

## Elevation
- **Soft Shadows**: Used on elements like the achievements section container to create subtle depth (`box-shadow: 0 10px 30px rgba(0,0,0,0.3)`).
- **No Heavy Outlines**: Prefer flat color blocks and soft container elevations over sharp high-contrast border styles.

## Components
- **Card**: Features rounded corners of `10px` and large padding (`24px` to `30px`) for high scannability and layout breathing room.
- **Buttons**: Structured with a subtle hover zoom or shift and a rounded radius of `4px`.

## Do's and Don'ts
- **DO** use `display: flex` and `margin: 0 auto` to keep containers centered.
- **DO** ensure high contrast (minimum 4.5:1 ratio) on text overlays.
- **DON'T** stack text and number icons vertically where inline flow is expected (use flexbox and `white-space: nowrap`).
- **DON'T** use highly corporate templates (like dark grids or sterile gray/blue charts).
