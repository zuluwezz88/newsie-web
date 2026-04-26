# Newsie — App Store / Play Store launch copy

Source of truth for App Store Connect + Google Play Console listings.
Paste from here when filling in the developer console paperwork.

Last updated: 2026-04-26.

---

## App Store Connect (iOS)

**App name** (max 30): `Newsie` *(6/30)*

**Subtitle** (max 30): `Your morning paper, delivered` *(28/30)*

**Promotional text** (max 170, updateable without resubmission):
> One finite edition each morning at 9:30am. No algorithm, no infinite scroll, no ads. Read it with your coffee, then close the app. That's the whole idea.

*(158/170)*

**Description** (max 4000):

```
Newsie is a calmer way to read the news.

One finite daily edition, delivered at 9:30am. No infinite scroll. No algorithm choosing what you see next. No outrage cycle. When you've read today's paper, you're done — close the app and get on with your day.

If you've ever felt exhausted by the news but unable to look away, Newsie is built for you. We pull the day's headlines from publishers you already trust — BBC, NPR, the Verge, Wired, ESPN, and others — and rewrite them in a calm, neutral editorial voice. Every story is short enough to read in a minute, links back to the original publisher, and sits next to its original wire-service headline so you can see exactly what was rewritten.

What's in your daily edition:

· Today's news, summarized — the morning's headlines across world, US politics, markets, tech, culture, and sports. You pick the beats you care about during onboarding.

· The Governor — a 5-minute audio briefing in a calm British anchor voice. Listen on your commute, in the kitchen, on a walk.

· The Typesetter — a daily three-word puzzle drawn from the top story. Brain food that isn't doomscrolling.

· Your streak — a small flame that grows the more days in a row you read.

· Three reading themes — bright daylight, OLED-friendly dark, and a warm sepia comfort mode for late-night or early-morning reading.

A few promises:

· No ads, ever.
· No account required. Newsie doesn't collect your name, email, or browsing history. Your streak and theme preferences live only on your device.
· No infinite scroll. When you reach the end of today's edition, the app tells you "you're done."
· No clickbait. Our editorial guidelines forbid hype words, all-caps headlines, fake-suspense leads, and invented quotes. If a detail isn't in the source story, we leave it out.
· Transparent summaries. Every article shows its original wire-service headline. We summarize, we don't reproduce. Publishers can request removal at any time.

Newsie is made by an indie builder. There's no marketing team and no algorithmic optimization. Just a thoughtful daily paper, made with care, for readers who want to be informed without being overwhelmed.

Welcome to Newsie. Here's your paper.
```

*(~2,400 / 4,000 — room to expand if needed)*

**Keywords** (max 100 chars total, comma-separated, NO spaces):
> `daily,briefing,podcast,minimalist,morning,paper,quiet,digest,mindful,focus`

*(73/100)*

(Apple auto-indexes words from name + subtitle, so don't repeat "news", "calmer", "morning", "paper" — already there. Adjust above if you change subtitle.)

**Category:** Primary = `News` · Secondary = `Lifestyle`

**Age rating:** Likely **12+** (standard for news apps covering world events / politics — questionnaire will confirm)

**URLs:**
- Privacy Policy URL: `https://afterhours-lab.github.io/newsie-web/privacy.html`
- Marketing URL (optional): `https://afterhours-lab.github.io/newsie-web/`
- Support URL: `https://github.com/afterhours-lab/newsie-web/issues`

---

## Google Play Console (Android)

**App title** (max 30): `Newsie`

**Short description** (max 80, shows in search results):
> `A calmer way to read the news. One finite edition every morning at 9:30.`

*(72/80)*

**Full description** (max 4000): same copy as the iOS Description above.

**Category:** `News & Magazines`

**Tags:** Pick ~5 from Google's preset list. Likely candidates:
- Daily news
- Morning briefing
- Podcasts
- Minimalist
- Calm

**Content rating:** Run the questionnaire — Newsie should land at `Teen` (Google's rough equivalent to Apple's 12+).

---

## Screenshots (Phase 3 todo)

Required iOS sizes:
- **6.7"** (iPhone 15 Pro Max, iPhone 14 Pro Max) — 1290×2796
- **5.5"** (iPhone 8 Plus) — 1242×2208

Required Android: at least 2 phone screenshots, plus 1 feature graphic at 1024×500.

Suggested shot list (4–6 screens):
1. **Newsstand** — onboarding beat picker (newspaper-style cards)
2. **Today's edition** — first article expanded, original headline visible
3. **Audio player open** — The Governor briefing
4. **Puzzle** — The Typesetter
5. **Settings** — themes / daily reminder toggle
6. **Done screen** — READ stamp + "Drop a coin in the tin"

Capture in iOS Simulator (Xcode) or directly on iPhone with Expo Go for now. Once a dev build / TestFlight is up, recapture with the production build.

---

## Tip jar

Buy Me a Coffee: `https://buymeacoffee.com/newsieapp`

Wired into Done screen as `Drop a coin in the tin ☕` (commit `f17fee6`).
