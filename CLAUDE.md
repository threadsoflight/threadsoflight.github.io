# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a static website for "Threads of Light" - a transformative card-based connection game designed to foster meaningful human connections through vulnerability, kindness, and authentic sharing. The site serves as a marketing/landing page with sections for product information, testimonials, and a waitlist signup.

## About Threads of Light (The Game)

**Threads of Light** is a card game that helps people connect more deeply through meaningful conversations, creative challenges, and playful activities. Instead of small talk, players share stories, get creative, and discover amazing things about each other.

### Game Mechanics
- **Three difficulty levels**: SPARK ✨ (1 thread), GLOW 🔥 (2 threads), SHINE 💫 (3 threads)
- **No elimination**: Everyone participates at their comfort level
- **Flexible participation**: "My Own Way" option, partner cards, ability to pass
- **Goal**: Earn 20 threads while creating meaningful connections
- **Players**: 3-8 people, 60-90 minutes
- **Core philosophy**: Connection over competition, authenticity over performance

### Key Values
- Authentic connection through vulnerability as strength
- Inclusive safety where everyone can participate fully
- Playfulness in meaningful interactions
- Individual recognition and storytelling power
- Present moment awareness and connection over competition

## Architecture

- **Static HTML/CSS website** with no build process required
- **Single-page application** structure with all content in `index.html`
- **GitHub Pages deployment** configured via CNAME file pointing to `threadsoflight.games`
- **Embedded Tally form** for waitlist collection integrated via iframe

### File Structure
- `index.html` - Main landing page with all sections (hero, about, testimonials, waitlist)
- `style.css` - Basic CSS styles (appears unused in current implementation)
- `css/style-squarespace.css` - Primary stylesheet with Squarespace-inspired design
- `images/` - Image assets (logo, hero image, about image, split section image)
- `CNAME` - GitHub Pages custom domain configuration

## Design System

**Color Palette:**
- Primary gold: `#c5a572`
- Dark green: `#354a33` 
- Sage grey: `#8a8b7a`
- Soft cream: `#f4f4f0`
- Light backgrounds: `#fefefe`, `#ebe5dc`

**Typography:**
- Primary: 'Poppins' for body text
- Secondary: 'Crimson Text' for headings
- Additional fonts: Inter, Athelas, Montserrat, Avenir Next

## Key Features

1. **Responsive hero section** with centered logo and navigation
2. **Three-tier game explanation** (SPARK, GLOW, SHINE cards)
3. **Testimonials grid** with customer feedback
4. **Embedded Tally waitlist form** with custom styling
5. **Scroll-triggered navigation** that appears after 100px scroll
6. **PayPal integration ready** (commented out for future use)

## Development Commands

This is a static website with no build process. To work with it:

- **Local development**: Open `index.html` directly in browser or use any local server
- **Deployment**: Automatic via GitHub Pages when pushed to main branch
- **Domain**: Site deploys to `threadsoflight.games` via CNAME configuration

## Content Management

- All content is hardcoded in `index.html`
- Images are stored in `/images/` directory
- Form submissions handled by Tally (external service)
- No database or CMS - purely static content

## Related Repository

The game design files, rules, and card content are maintained in the separate `../threads-of-light/` repository, which contains the complete game documentation, card generation scripts, and printable assets.