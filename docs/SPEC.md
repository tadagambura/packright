# PackRight: Spec

**Packing lists you never write twice** · #32 of 33 · Wave 3: Seasonal and episodic · Used: Per trip · Very easy · Revenue potential: Low–medium · Plans, Trips & Occasions · Source: New (Claude)

## One-liner

Reusable packing lists by trip type (beach, city break, festival, ski, business, travelling with a baby) that you tick off as you pack. Lists improve each trip: things you never used drop off, things you forgot get added.

## Problem / audience

- **Who it's for:** Holidaymakers, festival-goers, frequent travellers, parents packing for kids.
- **The problem it solves:** People rewrite the same list every trip and still forget chargers and passports.
- **Example:** Packing for a festival, a user opens their saved festival list, ticks everything off, and adds 'power bank' after forgetting it last year.

## MVP features (ship with only these)

1. Template lists by trip type
2. Tick off while packing; 'pack for home' mode
3. Personal lists that improve every trip
4. Trip countdown
5. Share a list with travel companions

## Not in MVP

- Weather-aware suggestions
- Shared group lists (sync)
- Hand-luggage liquid and weight checks

## Monetisation

| Model | Detail |
|---|---|
| Free | Templates and 3 saved lists, with ads |
| Premium | £2.99 lifetime: unlimited lists, sharing, no ads |
| Affiliate | Travel gear links, clearly labelled |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Trip date approaching |
| Tiny win | Tick items |
| Progress | % packed |
| Share | Lists shared with travel companions |
| Next step | After the trip: 'what didn't you use?' to improve the list |
| Cadence | Per trip |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- The suitcase zips shut at 100% packed


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app; templates also as SEO web pages.
- **Data:** On the device only.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Packing lists; Travel hacks; Festival prep
- **Shareable output:** Lists shared with travel companions

## Risks

Used only around trips. Its job is search traffic and cross-promotion, not big revenue.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
