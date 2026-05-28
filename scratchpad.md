# AIBridge Investor Deck — Plan

## Aesthetic from app.aibridge.one
- Deep navy background `#080B14` → subtle gradient `#0B0F1C`
- Card surface `#0F1424` with 1px `rgba(148,163,184,0.10)` border
- Primary text `#F1F5F9` / secondary `#94A3B8` / tertiary `#64748B`
- Brand gradient: `linear-gradient(135deg, #38BDF8 0%, #8B5CF6 100%)`
- Category accents: cyan `#38BDF8`, violet `#8B5CF6`, green `#34D399`, orange `#FB923C`
- Type: Inter for UI/body (close stand-in for Geist Sans), JetBrains Mono for code-label accents
- Visual signatures: thin-border cards, monospace eyebrows (`THE INCOME SEEKER`), gradient text on hero phrases, dot connectors, subtle dotted/grid background, glow on numbered step badges

## Type & Spacing tokens (in CSS vars)
- --type-title: 56px (user said no very big headings)
- --type-subtitle: 36px
- --type-display: 96px (only for hero stats)
- --type-body: 26px
- --type-small: 20px
- --type-eyebrow: 14px (mono, 0.18em tracking, uppercase)
- --pad-x: 100px, --pad-top: 88px, --pad-bottom: 72px
- --gap-title: 40px, --gap-item: 24px

## Title sequence (short topic noun-phrases, mono eyebrows)
01. Cover — AIBridge Holdings · Investor Deck 2026
02. The Human Crisis
03. The Economic Crisis
04. The Gap
05. The Insight
06. The Solution
07. The Socrates Engine
08. User Archetypes
09. Traction
10. Market Opportunity
11. Business Model
12. Go-to-Market
13. Competitive Landscape
14. Team
15. Financial Model
16. The Ask
17. Sources & Notes
18. Closing

## Per-slide layout shorthand
01 Cover — left aligned wordmark + gradient phrase, orbital nodes graphic right
02 Human crisis — big stat 300M left, vertical anxiety/burnout chip column right, attribution footer
03 Economic crisis — three stat cards $4.4T / 300M / $9T, all with source mono caption
04 The Gap — 3-column compare table (What Exists / The Gap / What People Need)
05 The Insight — quote slide w/ founder journey timeline (Apple → GoToRetreats → GoToStudio → AIBridge)
06 The Solution — three reinforcing brand cards w/ icons + flywheel footer line
07 Socrates Engine — 4-step row with numbered badges (gradient)
08 Archetypes — 4-up card grid w/ accent color per archetype
09 Traction — 4 big-stat tiles + "Already built / $2M unlocks" two columns
10 Market — TAM/SAM/SOM nested visual (concentric or stacked bars)
11 Biz Model — 4-card revenue streams, each with $ range
12 GTM — 4-step horizontal w/ connector
13 Competitive — comparison matrix w/ filled/empty dots
14 Team — single card (founder bio) + Hiring + Advisors columns
15 Financials — animated bar chart Y1 → Y3 + 3 stat columns
16 The Ask — $2M big number + 5 allocation chips/bars
17 Sources & Notes — 2-column reference list, small mono
18 Closing — centered gradient phrase

## Animations
- Cover: orbital nodes pulse + connection lines draw on load
- All slides: fade+rise on activation (deck-stage hook)
- Slide 9 stats: count-up on activation
- Slide 15: bar chart grow on activation
- Subtle dotted grid background, persistent
