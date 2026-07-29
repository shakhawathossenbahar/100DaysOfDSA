# DSA Journey — Reusable Master Poster Prompt
### Only change the two variables below. Everything else is fixed.

```
DAY_NUMBER = Day 1
TOPIC = Algorithm
```

---

## PROMPT (copy everything below, fill in the two variables at the top)

Create a professional infographic-style poster for a coding learning journey series.

VARIABLES FOR THIS IMAGE:
- Day: {{DAY_NUMBER}}
- Topic: {{TOPIC}}

Using the Topic above, intelligently generate ALL the following content yourself, matching the depth and format of a real C++ / DSA study note. Do not ask for more input — infer everything below directly from the Topic:
- A short, accurate subtitle for the topic (2–4 words)
- 4 short "Today I Learned" sub-concepts belonging to this Topic, each with a matching minimal line icon
- 4 content-card sections, each covering one key idea within the Topic, with a 1–2 line plain-English explanation and a short, correct, compilable C++ code snippet (4–8 lines) demonstrating it
- Where relevant, a small reference box next to a code card (e.g. a short table, complexity list, or definition list) — only include this if it naturally fits the section, otherwise omit it
- 3 "Key Takeaway" bullet insights specific to this Topic
- 4 "Things I Practiced Today" checklist items specific to this Topic
- 1 short original italic motivational quote (max 20 words) thematically tied to this Topic

IMAGE SPECS:
- Resolution: 2160 x 2700 pixels (4:5 portrait aspect ratio)
- High resolution, sharp, crisp text — optimized for both LinkedIn desktop and mobile feed display without cropping
- Safe margin of 60px on all edges — no text or icons touching the border

COLOR THEME (fixed — use exactly, never substitute):
Background: Warm Pearl White (#FAFAF8), Soft Champagne Ivory (#F5F1E8)
Primary Accent: Deep Charcoal (#1C1C1E)
Secondary Accent: Graphite Slate (#3A3D42)
Highlight Color: Champagne Gold (#C9A567)
Supporting Colors: Warm Gray (#8A8580), White (#FFFFFF), Soft Bronze (#B08D57), Pale Stone (#E8E4DC)
Avoid bright green, saturated reds, and any neon/saturated colors. Muted, elegant, premium editorial look — not a tech-startup app.

TOP SECTION:
- Small circular logo badge (top-left), Charcoal fill with thin Gold ring, containing a minimal `</>` mark, beside "DSA Journey" wordmark in bold Charcoal sans-serif
- Bold heading: "DSA Journey with C++" (large, Charcoal, bold sans-serif)
- Flat rounded banner (Charcoal fill, clean geometric shape, no brush-stroke texture) with huge bold Gold text showing {{DAY_NUMBER}}
- Small `{ }` icon in Gold, and a minimal line-art laptop-and-plant illustration in Charcoal/Graphite/Gold on the right
- Subtitle pill banner below, Graphite Slate fill, White bold text, showing the generated subtitle for {{TOPIC}}

"TODAY I LEARNED" ROW:
- Pill-shaped header bar, Charcoal fill, Gold bold text: "TODAY I LEARNED"
- 4 rounded-square cards in a row (White fill, Pale Stone border, subtle shadow), each with a Gold line icon + the 4 generated sub-concept labels

CONTENT SECTIONS (2-column grid, White cards, Charcoal numbered header bars "01"–"04"):
- Each card: generated section title → 1–2 line explanation → dark code-editor box (Charcoal #1C1C1E background, monospace font, syntax highlighting in Gold/Bronze/White only, no green) with the generated code snippet
- Add the optional small reference box beside the code only where it naturally fits

BOTTOM SECTION:
- "KEY TAKEAWAY" card — lightbulb icon (Gold), Charcoal header bar, White body, the 3 generated takeaway bullets
- "THINGS I PRACTICED TODAY" card — Gold checkmark icons, Charcoal header bar, the 4 generated checklist items
- Quote card — target/goal icon (Gold), Charcoal header bar, the generated italic quote, centered

FOOTER:
- Thin dotted divider (Pale Stone) with small Gold leaf/swirl accents at each end
- Centered closing line, Charcoal bold text, small Gold heart icon: "Keep Learning. Keep Growing."

STYLE:
Clean flat-design illustration style, Deep Charcoal (#1C1C1E) as the single primary accent against warm pearl/champagne-ivory background, Champagne Gold (#C9A567) as the sole highlight color. Rounded corners on all cards. Bold sans-serif for headers, monospace for code. Subtle dotted/leaf decorations confined to corners and footer, in Gold or Pale Stone only. All text sharp and fully readable at mobile-thumbnail scale.

---

## HOW TO USE FOR EACH NEW POST
1. Copy the whole prompt block above.
2. Replace `{{DAY_NUMBER}}` → e.g. `Day 2`
3. Replace `{{TOPIC}}` → e.g. `Array`
4. Paste into your image generator. That's it — everything else (icons, code, takeaways, quote) is generated to match the new topic automatically, in the exact same locked layout and color scheme.