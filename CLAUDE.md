# Cultivate — Grace Women's Conference

One-page QR-code resource landing page for the Cultivate Women's Conference at Grace Calvary Chapel, Saturday April 25, 2025. Women at the conference scan a QR code to access this page on their phones.

## Stack

- **Vite** static site (no framework — plain HTML/CSS)
- **Tailwind CSS** via CDN in `index.html`
- **Custom CSS** in `style.css` (design system, all components)
- **Deploy target:** Vercel (`vercel.json` — framework auto-detected)

## Development

```bash
npm install
npm run dev        # http://localhost:5173
npm run build      # output → dist/
npm run preview    # preview built output locally
```

## Deploy

Push to GitHub and import the repo in Vercel. No environment variables needed. Vercel auto-detects Vite.

---

## Design System

| Token             | Hex       | Use                                  |
|-------------------|-----------|--------------------------------------|
| `--cream`         | `#F5EDE4` | Page background                      |
| `--cream-light`   | `#FAF5F0` | Schedule section background          |
| `--terracotta`    | `#C0392B` | Primary accent, sessions, links      |
| `--terracotta-light` | `#E8714A` | Gradient start, warm accents      |
| `--botanical`     | `#4A5E3A` | Worship items, devotional category   |
| `--teal`          | `#1a6b7c` | Grace Calvary Chapel brand, community|
| `--text`          | `#2C1810` | Body text                            |
| `--text-mid`      | `#5C3D2E` | Secondary text                       |

**Fonts (Google Fonts):**
- `Cormorant Garamond` — elegant serif for all headings
- `Lato` — clean sans-serif for body text
- `Great Vibes` — script accent (available for decorative use)

---

## Files That Need Replacing

Place these files in the `public/` folder before publishing:

| File | Notes |
|------|-------|
| `public/cultivate-logo.png` | Cultivate wordmark PNG. Use transparent background if possible — otherwise the CSS `mix-blend-mode: multiply` on the hero will blend it into the cream background naturally. |
| `public/bg-botanical.png` | Warm cream botanical slide (1920×1080). Used as hero background. |
| `public/sarah-enterline.jpg` | Speaker headshot. Will display in a 160×160 circular crop. If not present, initials "SE" appear as fallback. |
| `public/grace-logo-white.png` | ✅ Already copied from Desktop. White horizontal Grace logo for dark footer. |

---

## Resources (26 placeholder PDFs)

All placeholder files are in `public/resources/`. Replace each empty `.pdf` file with the real document before the conference.

### Category 1 — Session Notes & Scripture (8 files)
- `session-1-deeply-rooted.pdf`
- `session-2-pruned-and-pressed.pdf`
- `session-3-becoming-the-sower.pdf`
- `session-4-qa-discussion-guide.pdf`
- `conference-key-scriptures.pdf`
- `sermon-notes-template.pdf`
- `application-reflection-questions.pdf`
- `memory-verses.pdf`

### Category 2 — Devotional & Spiritual Growth (9 files)
- `30-day-cultivate-devotional.pdf`
- `daily-quiet-time-guide.pdf`
- `prayer-journal-template.pdf`
- `scripture-memorization-cards.pdf`
- `spiritual-disciplines-guide.pdf`
- `womens-bible-reading-plan.pdf`
- `gratitude-reflection-worksheet.pdf`
- `john15-vine-branches-study.pdf`
- `morning-prayer-guide.pdf`

### Category 3 — Community & Next Steps (9 items)
- `grace-womens-ministry-overview.pdf`
- `small-group-study-guide.pdf`
- `mentorship-program-info.pdf`
- `recommended-books-list.pdf`
- Sarah Enterline's website (external link — no file needed)
- `womens-bible-study-schedule.pdf`
- `volunteer-serve-at-grace.pdf`
- `connect-card.pdf`
- `prayer-counseling-ministry.pdf`

---

## Schedule

| Time | Item |
|------|------|
| 8:30–9:00 AM | Arrival — Coffee, Mini Muffins, Juice |
| 9:00–9:20 AM | Opening Worship |
| 9:20–9:30 AM | Welcome & Intro (Ashley) |
| 9:30–10:15 AM | **Session 1: Deeply Rooted** (Sarah) |
| 10:15–10:30 AM | Break |
| 10:30–11:30 AM | **Session 2: Pruned and Pressed** (Sarah) |
| 11:30 AM–12:30 PM | Lunch |
| 12:30–12:50 PM | Afternoon Worship |
| 12:50–1:30 PM | **Session 3: Becoming the Sower** (Sarah) |
| 1:30–2:15 PM | Craft |
| 2:15–2:45 PM | Dessert Bar |
| 2:45–3:45 PM | **Session 4: Pair & Share / Q&A / Resources** (Ashley & Sarah) |
| 3:45–4:00 PM | Closing Worship |

---

## Speaker

**Sarah R. Enterline** — author, apologist, pastor's wife, teacher, women's ministry leader  
Website: https://www.sarahrenterline.com  
Books page: https://www.sarahrenterline.com/books

Books featured:
1. *No Apologies: The Life and Work of Susanna Newcome*
2. *Digging Deeper: The Life and Work of Mary Brodrick*
3. *Stand Therefore: A Practical Guide to Spiritual Warfare*
4. *A Visual Guide to Biblical Apologetics*
