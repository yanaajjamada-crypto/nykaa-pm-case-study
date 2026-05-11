# 💄 Nykaa Product Case Study
## Improving Product Discovery & Conversion on Nykaa

> **Type:** Product Management Case Study | Product Teardown + Feature Proposal  
> **Author:** Yana Ajjamada | M.Sc. Organic Chemistry → Product Management  
> **Status:** Concept project — demonstrates end-to-end PM thinking  

---

## ⚠️ Disclaimer

This is an independent product case study created for portfolio purposes. I am not affiliated with Nykaa. All pain points, user personas, and proposed solutions are based on publicly available information, user reviews, and personal analysis. This project is intended to demonstrate product management thinking — problem framing, user research, competitive analysis, prioritisation, and success metrics.

---

## 📌 Problem Statement

Nykaa is India's leading beauty e-commerce platform with **over 2,500 brands and 1.8 million+ products**. But more choice doesn't always mean better outcomes.

Users — especially first-time beauty buyers — frequently experience **decision fatigue** when browsing Nykaa. The current product discovery experience relies on basic filters, category browsing, and generic "bestseller" rankings. It does not account for individual skin type, tone, concerns, or preferences.

**The result:**

- Users spend time browsing but leave without buying
- Cart abandonment rates rise when choices feel overwhelming
- First-time buyers lack confidence in product suitability
- Repeat buyers don't discover new products relevant to them
- Reviews feel unreliable — making purchase decisions harder, not easier

**The core insight:** Nykaa has a discovery problem, not a catalogue problem. The products exist. Users just can't find the right one for them.

---

## 🎯 Objective

> Increase conversion rate and user satisfaction by transforming Nykaa's product discovery experience through AI-powered personalisation, smarter filtering, and trustworthy social proof.

**Target outcome at 12 months post-launch:**
- 25% increase in conversion rate
- 30% reduction in cart abandonment
- 40% increase in repeat purchase rate among new users

---

## 📊 Market Context

| Metric | Value |
|---|---|
| Nykaa registered users | 35 million+ |
| Products listed | 1.8 million+ |
| Brands on platform | 2,500+ |
| Indian beauty & personal care market size | $28 billion (2023) |
| Projected market size by 2028 | $43 billion |
| Percentage of users who abandon cart | ~70% (industry average) |
| Percentage of adverse events that are preventable | Key stat: 60% of beauty purchases are driven by recommendations |

---

## 👤 User Personas

### Persona 1 — The Overwhelmed Beginner

**Name:** Ishita Sharma  
**Age:** 22 | **Location:** Jaipur | **Occupation:** College student  
**Device:** Mobile (primary), occasional desktop

> *"I want to start a skincare routine but every time I open Nykaa I spend 45 minutes scrolling and close the app without buying anything. I don't even know where to start."*

**Pain points:**
- Doesn't know her skin type or what ingredients to look for
- Gets overwhelmed by the number of options in any category
- Doesn't trust reviews — worried they're fake or paid
- Has a limited budget (~₹500–800 per product) and can't afford to make the wrong choice

**What she needs:**  
A guided starting point — a quiz or assessment that says "for your skin type, start with these three products." Confidence, not choice.

**Behaviour:**  
Browses Nykaa for 30–45 min sessions. Rarely converts on first visit. Responds to influencer content on Instagram but can't always find the exact product shown.

---

### Persona 2 — The Loyal Repeat Buyer

**Name:** Meera Nair  
**Age:** 31 | **Location:** Bengaluru | **Occupation:** Marketing manager  
**Device:** Mobile app

> *"I've been buying the same 5 products for two years. I know Nykaa has new launches but I never see them on my homepage. It always shows me things I've already bought."*

**Pain points:**
- Recommendations show products she already owns or has tried
- Discovery of new relevant launches is poor — she finds out from Instagram, not Nykaa
- Nykaa Black membership benefits aren't always visible or communicated clearly
- Wishes she could build a "routine stack" that tracks her current products and suggests what to add next

**What she needs:**  
A smarter recommendation engine that knows her history and surfaces genuinely new, relevant products — not repurchases. A loyalty-aware discovery feed.

**Behaviour:**  
High purchase frequency (2–3 orders/month). High lifetime value. Low churn risk but low discovery engagement — sticks to known products only.

---

### Persona 3 — The Research-First Buyer

**Name:** Divya Krishnamurthy  
**Age:** 27 | **Location:** Chennai | **Occupation:** Software engineer  
**Device:** Desktop (research), mobile (purchase)

> *"Before I buy anything I read every review, watch 3 YouTube videos, and check Reddit. I don't trust the reviews on Nykaa because I can't tell which ones are verified and which ones are incentivised."*

**Pain points:**
- Reviews on Nykaa don't indicate whether the reviewer has a similar skin type
- No way to filter reviews by skin type, tone, or concern
- Sponsored content and organic content look identical — she can't distinguish them
- Comparison between similar products (e.g., two vitamin C serums) requires opening multiple tabs

**What she needs:**  
Verified, filterable reviews. An AI sentiment summary that tells her what real users with her skin type actually experienced. A side-by-side product comparison tool.

**Behaviour:**  
Long research phase (3–7 days per purchase decision). High average order value (₹1,500–3,000). Rarely impulse buys. Becomes a loyal repeat buyer once she finds a product she trusts.

---

### Persona 4 — The Trend Chaser

**Name:** Zara Ahmed  
**Age:** 19 | **Location:** Mumbai | **Occupation:** Content creator / student  
**Device:** Mobile (exclusively)

> *"I see a product on Instagram or a YouTube short and I want to find it on Nykaa immediately. Half the time I can't even find it using the search bar."*

**Pain points:**
- Search doesn't handle colloquial names or social media product nicknames well
- "Trending" section on Nykaa doesn't reflect what's actually trending on social media
- No way to shop directly from influencer content within the app
- Flash sales and limited edition drops are hard to track

**What she needs:**  
Social media-integrated discovery. A trending section that actually reflects real-time social trends. Better search that understands "that Hailey Bieber skin tint" and maps it to the actual product.

**Behaviour:**  
High browse frequency, moderate purchase frequency. Responds to urgency — limited stock, flash sales. Strong social proof dependency — won't buy without seeing real-person reviews.

---

## 🔍 Deep Dive — User Pain Points

| Pain Point | Affected Personas | Frequency | Severity |
|---|---|---|---|
| Too many options, no personalisation | All | Very High | High |
| Unreliable or unhelpful reviews | Ishita, Divya | High | High |
| Poor recommendations for repeat buyers | Meera | High | Medium |
| Difficulty finding trending/new products | Zara, Meera | Medium | Medium |
| No routine-building or bundling tool | Ishita, Meera | Medium | Medium |
| Social media to app discovery gap | Zara | High | High |
| No skin-type filtered reviews | Divya, Ishita | High | High |

---

## 🏆 Competitive Analysis

### How Nykaa compares to key competitors

| Feature | Nykaa | Purplle | Sephora India | Myntra Beauty | Amazon Beauty |
|---|---|---|---|---|---|
| **Personalisation engine** | Basic — purchase history only | Moderate — quiz-based | Strong — profile-based | Weak — generic | Weak — purchase history only |
| **Skin type quiz / assessment** | No | Yes — onboarding quiz | Yes — Beauty Profile | No | No |
| **AI product recommendations** | Basic collaborative filtering | Quiz-based matching | AI-powered | Trend-based | Purchase-based |
| **Review authenticity signals** | Verified purchase badge only | Verified + skin type shown | Verified + detailed profiles | Verified purchase only | Verified purchase + Vine |
| **Review filtering by skin type** | No | Partial | Yes | No | No |
| **Routine builder** | No | Basic | Yes — Beauty Routine | No | No |
| **Social / influencer integration** | Partial — Nykaa TV | No | No | Yes — M-Live | No |
| **AR virtual try-on** | Yes — limited | No | Yes | No | No |
| **Product comparison tool** | No | No | No | No | No |
| **Search quality** | Moderate | Moderate | Good | Good | Excellent |
| **Private label products** | Strong — Kay Beauty etc. | Strong | Limited | Limited | Limited |
| **Price range** | Mid to Premium | Budget to Mid | Premium | All ranges | All ranges |

### Key competitive insight

**Nykaa's gap vs Purplle:** Purplle acquired users with a skin quiz at onboarding — a feature Nykaa still lacks. This is a direct threat in the beginner segment.

**Nykaa's gap vs Sephora:** Sephora's Beauty Profile creates a persistent personalisation layer that improves with every purchase. Nykaa's recommendations reset with each session.

**Nykaa's advantage:** Brand trust, catalogue depth, private label strength (Kay Beauty), and Nykaa TV for content. These are defensible moats — but only if discovery improves so users can find the right products within that catalogue.

**The opportunity:** No competitor in the Indian market has nailed the combination of personalised discovery + verified skin-type reviews + routine building. This is Nykaa's to win.

---

## 💡 Proposed Solution

### Feature 1 — Skin Profile Quiz (Onboarding + Persistent)

**What:** A 5-question quiz at onboarding and in profile settings that captures skin type, tone, primary concern (acne, pigmentation, dryness etc.), and budget range.

**Why:** Purplle proved this works for acquisition. Sephora proved it works for retention. Nykaa needs both.

**Output:** A persistent "Skin Profile" that powers all downstream personalisation — recommendations, filter defaults, and routine suggestions.

**Priority:** P0 — must have in MVP

---

### Feature 2 — AI-Powered Personalised Recommendation Engine

**What:** Replace generic "bestseller" and "trending" sections with a personalised discovery feed powered by:
- Skin profile data
- Purchase and browsing history
- Users-like-me collaborative filtering
- Real-time trend signals from social media

**Why:** 60% of beauty purchases are recommendation-driven. Nykaa's current engine is purchase-history only — it shows users what they've already bought, not what they should try next.

**Priority:** P0 — core product value

---

### Feature 3 — Smart Filters

**What:** Replace generic category filters (brand, price, rating) with context-aware smart filters:
- "Best for oily + acne-prone skin"
- "Beginner-friendly — 3 steps or less"
- "Dermatologist recommended"
- "Works well with [product she already owns]"
- "Under ₹500 — high rated"

**Why:** Basic filters don't solve the discovery problem — they just narrow a still-overwhelming list. Smart filters surface intent-matched products.

**Priority:** P1 — important

---

### Feature 4 — Review Authenticity & Skin-Type Filtering

**What:** Two improvements to the review system:
1. Show reviewer's skin type and tone on every review (opt-in during review submission)
2. AI sentiment summary: *"Among users with oily skin — 82% reported reduced shine within 2 weeks"*
3. Filter reviews by "skin type like mine"

**Why:** Reviews are the #1 trust signal in beauty — but only if they're relevant. A review from someone with dry skin means nothing to someone with oily skin.

**Priority:** P1 — important for conversion

---

### Feature 5 — Routine Builder

**What:** Based on the user's Skin Profile, Nykaa generates a personalised morning and night skincare routine:
- Recommends 3–5 steps
- Each step shows 2–3 product options at different price points
- "Add full routine to cart" button
- Tracks which routine products the user already owns

**Why:** Routine thinking increases basket size (multiple products per session) and repeat purchase rate (users come back to replenish routine products). It also helps beginners — Ishita's primary need.

**Priority:** P1 — retention driver

---

### Feature 6 — Social Discovery Integration

**What:** A "Trending Now" section powered by real-time social signals (Instagram, YouTube, Reddit India), not internal sales data. Users can search for products using social nicknames ("glazed donut skin moisturiser") and find the right product.

**Why:** Zara's journey starts on social media, not on Nykaa. If Nykaa can bridge that gap — be the place she lands after seeing something on Instagram — it captures high-intent traffic.

**Priority:** P2 — growth lever

---

## 🗺 MVP Plan & Roadmap

### Phase 1 — Foundation (Months 1–3)
*Goal: Build the personalisation layer that powers everything else*

- [ ] Skin Profile Quiz — onboarding + profile settings
- [ ] Persistent skin profile stored against user account
- [ ] Basic recommendation engine using skin profile + purchase history
- [ ] Verified reviewer skin type shown on review cards
- [ ] Smart filter: "Best for [skin type]"

### Phase 2 — Enhancement (Months 4–6)
*Goal: Improve trust and increase basket size*

- [ ] AI sentiment summary on product pages
- [ ] Review filtering by skin type
- [ ] Routine Builder — generates morning + night routine from skin profile
- [ ] "Add full routine to cart" functionality
- [ ] Improved recommendation engine — users-like-me collaborative filtering

### Phase 3 — Scale (Months 7–12)
*Goal: Social discovery and loyalty-driven retention*

- [ ] Trending section powered by real social media signals
- [ ] Social nickname search ("glazed donut skin product")
- [ ] Influencer content linked to exact products
- [ ] AR virtual try-on expansion (existing feature — improve coverage)
- [ ] Dermatologist-verified badge programme

---

## 📊 Success Metrics

### North Star Metric
> **Conversion rate** — the percentage of sessions that result in a completed purchase

### Supporting Metrics

| Metric | Baseline (estimated) | Target at 6 months | Why it matters |
|---|---|---|---|
| Conversion rate | ~2.5% (industry avg) | 3.2% (+28%) | Primary success indicator |
| Add-to-cart rate | ~15% | 20% (+33%) | Measures discovery quality |
| Cart abandonment rate | ~70% | 55% (-21%) | Measures purchase confidence |
| Session duration | 8 min avg | 10 min avg (+25%) | Measures engagement |
| Repeat purchase rate (new users, 90 days) | ~20% | 30% (+50%) | Measures personalisation effectiveness |
| Routine Builder adoption | 0% (new feature) | 15% of active users | Measures feature success |
| Skin Profile completion rate | 0% (new feature) | 60% of new users | Powers all personalisation |

### Guardrail Metrics
*(Metrics that must NOT get worse)*
- App rating must stay above 4.2
- Page load time must not increase
- Return/refund rate must not increase (personalisation must not mislead)

---

## ⚖️ Trade-offs & Risks

| Risk | Impact | Severity | Mitigation |
|---|---|---|---|
| Users don't complete the skin quiz | Personalisation engine has no data to work with | High | Make quiz optional but incentivise with "your personalised picks" preview. Show value before asking for data. |
| AI recommendations feel inaccurate early | Users lose trust and ignore recommendations | High | Start with rule-based recommendations (skin type matching), layer AI on top as data grows. Be transparent about why a product is recommended. |
| Privacy concerns around skin data collection | Users refuse to share skin profile data | Medium | Clear, minimal data collection. Explicit opt-in. Store only what's needed. Allow profile deletion at any time. |
| Review skin-type data is sparse initially | Sentiment summaries are based on too few data points | Medium | Only show skin-type summaries when n > 50 reviews with skin type data. Default to overall summary otherwise. |
| Development cost and timeline | Features delayed, phased plan disrupted | Medium | Prioritise ruthlessly — Skin Profile Quiz + basic personalisation in Phase 1 is minimum viable. Other features can slip without losing core value. |
| Cannibalisation of editorial/influencer revenue | Smart recommendations may bypass sponsored placements | Low | Design recommendation engine to maintain sponsored slot allocation. Work with brand team on integration. |

---

## 🧮 Prioritisation Framework

Features were prioritised using the **RICE framework** (Reach × Impact × Confidence ÷ Effort):

| Feature | Reach | Impact | Confidence | Effort | RICE Score | Priority |
|---|---|---|---|---|---|---|
| Skin Profile Quiz | High | High | High | Low | 🔴 Very High | P0 |
| Personalised recommendations | High | High | High | Medium | 🔴 Very High | P0 |
| Smart filters | High | Medium | High | Low | 🟠 High | P1 |
| Review skin-type filtering | Medium | High | High | Medium | 🟠 High | P1 |
| Routine Builder | Medium | High | Medium | Medium | 🟠 High | P1 |
| Social discovery integration | Medium | Medium | Medium | High | 🟡 Medium | P2 |
| AR virtual try-on expansion | Low | Medium | Low | High | 🟢 Low | P3 |

---

## 🚀 Future Scope

- **AR virtual try-on** — expanded to all makeup categories, not just select products
- **Voice-based shopping assistant** — "Find me a moisturiser for dry skin under ₹600"
- **Dermatologist consultation integration** — book a 10-minute skin consult inside the app, recommendations powered by the outcome
- **Subscription routine replenishment** — auto-reorder routine products before they run out
- **Community layer** — user-generated routines, before/after sharing, peer recommendations

---

## 🧠 Why This Matters

India's beauty market is growing at 8.9% CAGR and is projected to reach $43 billion by 2028. Nykaa is the category leader — but category leadership in e-commerce is never permanent. Purplle is growing fast in Tier 2 cities. Myntra Beauty is leveraging fashion's existing user base. Reliance Retail is entering the space.

The brands that win in beauty e-commerce won't win on catalogue size — they'll win on **knowing their user better than anyone else**. That's a personalisation and discovery problem. And it's exactly what this proposal solves.

---

## 👩‍💼 About the Author

**Yana Ajjamada** | M.Sc. Organic Chemistry → Product Management

With a background in pharmaceutical chemistry and AI-based research at Microlabs Kudlu, I bring domain depth in science-adjacent products and a strong interest in consumer tech, healthcare, and beauty-tech.

This Nykaa case study is part of my PM portfolio alongside:

- **StabilityAI** — a real, built AI tool that predicts pharmaceutical degradation pathways (M.Sc. research project)
- **MediSafe AI** — a PM concept case study for an AI-powered drug safety checker

📎 GitHub: [github.com/yanaajjamada](https://github.com/yanaajjamada)

---

## 📁 Repository Structure

```
nykaa-pm-case-study/
│
├── README.md                  ← You are here — full case study
├── problem-statement.md       ← Deep dive on the problem space
├── competitive-analysis.md    ← Full competitor breakdown
├── personas.md                ← Detailed user persona profiles
├── solution.md                ← Feature specs and user stories
├── metrics.md                 ← Success metrics and measurement plan
├── prioritisation.md          ← RICE framework and trade-off decisions
└── wireframes/                ← Add Canva mockups here
    ├── skin-quiz-screen.png
    ├── personalised-feed.png
    ├── routine-builder.png
    └── review-filters.png
```

---

*This is an independent product case study created for portfolio purposes. Not affiliated with Nykaa FSN E-Commerce Ventures Ltd.*
