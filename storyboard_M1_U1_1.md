# Storyboard: What is Data-Driven Decision Making?
**Module 1 | Unit 1 | Duration: 5:00**
**Format:** Split screen — Narrator LEFT (40%) / Animated visuals RIGHT (60%)
**Style:** Clean flat-design illustration, bright but professional palette, warm neutrals + blue/amber accents

---

## LAYOUT KEY

```
┌──────────────────────────────────────────────────────────┐
│  NARRATOR (40%)          │  ANIMATED VISUALS (60%)        │
│  Talking head,           │  Icons, maps, charts,          │
│  professional setting    │  text reveals, animations      │
└──────────────────────────────────────────────────────────┘
```

Each panel = one visual beat. Annotations follow the format:
`Shot | Movement | Duration | Action | Dialogue/TOS | SFX/Music`

---

---

# SEGMENT 1 — Opening Story [0:00–0:40]

---

## Panel 1.1 — Title Card

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator smiles at camera, welcoming tone              │
│  RIGHT: Title card animates in —                              │
│         "Module 1, Unit 1:                                     │
│          What is Data-Driven                                   │
│          Decision Making?"                                     │
│         Subtitle fades in below: clean sans-serif font        │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), Static title card (right)               │
│ Movement: Title slides up from bottom, 0.5s ease-in           │
│ Duration: 0:00–0:06 (6 sec)                                   │
│ Action: Narrator opens with greeting                          │
│ Dialogue: "Hello, and welcome to Module 1, Unit 1 of the      │
│            Data-Driven Decision Making."                       │
│ TOS: "Module 1, Unit 1: What is Data-Driven Decision Making?" │
│ Music: Light, curious, upbeat intro sting                     │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "professional educator narrator, medium close-up, warm studio lighting, neutral background, friendly expression, educational video style, clean flat illustration",
  "width": 1248, "height": 832
}'
```

---

## Panel 1.2 — City Map Intro

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator leans slightly forward, storytelling tone     │
│  RIGHT: Bird's-eye stylised city map of an Indian city,       │
│         warm flat-design illustration. Delivery truck icons   │
│         scattered across the map. No zone highlighted yet.    │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: WS / Bird's Eye (map), MCU (narrator)                   │
│ Movement: Map fades in; trucks animate in one by one          │
│ Duration: 0:08–0:18 (10 sec)                                  │
│ Action: Map appears as narrator sets up the story             │
│ Dialogue: "A company in India was losing customers because    │
│            of delivery delays."                               │
│ TOS: (none)                                                   │
│ SFX: Soft city ambience, truck icon pop sound                 │
│ Music: Continues, slightly tense undercurrent                 │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "bird eye view stylised flat design city map of Indian city, delivery truck icons scattered across districts, warm color palette, clean educational illustration style, no text",
  "width": 1248, "height": 832
}'
```

---

## Panel 1.3 — Northern Zone Highlighted

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator points upward / north gesture                 │
│  RIGHT: Same city map. Northern zone pulses with amber        │
│         highlight. Bar chart inset shows delay spikes in      │
│         northern zone. Data readout: "Most delays: NORTH"     │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: WS / Bird's Eye (map), MS (narrator)                    │
│ Movement: Zone highlight pulses in; bar chart slides up       │
│ Duration: 0:08–0:18 (overlapping, ~6 sec beat)               │
│ Action: Data insight revealed — northern delays               │
│ Dialogue: "They checked their data. It was clear that most   │
│            delays occurred in the northern part of their      │
│            city."                                             │
│ TOS: "Most delays: NORTH ↑"                                   │
│ SFX: Data ping/reveal sound                                   │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 1.4 — Staff Move North

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator mimes moving pieces on a board                │
│  RIGHT: Staff/person icons (blue) animate from centre and     │
│         east of map → converge toward northern zone.          │
│         Arrow pointing north. Small ✓ satisfaction icon.      │
│         Eastern zone now visibly emptier.                     │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: WS / Bird's Eye (map), MS (narrator)                    │
│ Movement: Icons slide north with motion trails                │
│ Duration: 0:18–0:25 (7 sec)                                   │
│ Action: Staff reallocation visualised                         │
│ Dialogue: "So, they moved all their extra delivery staff      │
│            to the north."                                     │
│ TOS: (staff moving arrow)                                     │
│ SFX: Whoosh sound as icons move                               │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 1.5 — Delays Worse (Red Arrow Up)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 5                                             │
│                                                                │
│  LEFT: Narrator raises eyebrows — "but wait" expression       │
│  RIGHT: Delay counter/meter animation. Numbers tick UP        │
│         sharply. Large red upward arrow. Concerned face icon. │
│         Background: map still visible, now both north AND     │
│         east showing red delay indicators.                    │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), animated counter (right)                │
│ Movement: Counter ticks up rapidly; red arrow grows           │
│ Duration: 0:25–0:32 (7 sec)                                   │
│ Action: Reveal — situation got worse                          │
│ Dialogue: "Two months later, delays were worse than before."  │
│ TOS: Delay counter ↑↑ red arrow                               │
│ SFX: Rising alarm tone, tick-tick sound                       │
│ Music: Tension spike                                          │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design dashboard showing rising delay counter with large red upward arrow, warning indicator, concerned emoji icon, clean educational infographic style, red and amber palette",
  "width": 1248, "height": 832
}'
```

---

## Panel 1.6 — Question Mark / Punchline

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 1 — SHOT 6                                             │
│                                                                │
│  LEFT: Narrator pauses. Direct eye contact. Calm, knowing.    │
│  RIGHT: Large question mark over city map.                    │
│         Two text boxes appear:                                │
│           [✓ Data: Correct]   [✗ Question: Wrong]            │
│         Then bold pull-quote fades in below:                  │
│         "Good data. Wrong question. Bad decision."            │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), static graphic (right)                  │
│ Movement: Question mark drops in; text boxes pop in L then R  │
│ Duration: 0:32–0:40 (8 sec)                                   │
│ Action: Punchline delivered                                    │
│ Dialogue: "Good data. Wrong question. Bad decision."          │
│ TOS: "✓ Data: Correct" | "✗ Question: Wrong"                 │
│       "Good data. Wrong question. Bad decision."              │
│ SFX: Soft gavel/click on each text box                        │
│ Music: Resolves to pause beat                                 │
└────────────────────────────────────────────────────────────────┘
```

---

---

# SEGMENT 2 — Definition [0:40–1:15]

---

## Panel 2.1 — Three Icons: Evidence

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 2 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator holds up one finger                           │
│  RIGHT: Single icon appears centre-right:                     │
│         Magnifying glass (teal/blue), label below:            │
│         "EVIDENCE" — numbers, records, patterns               │
│         Rest of screen is empty (icons not yet revealed)      │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), icon close-up (right)                    │
│ Movement: Icon scales in from 0 with bounce                   │
│ Duration: 0:40–0:46 (6 sec)                                   │
│ Action: First element of DDDM definition introduced           │
│ Dialogue: "It comes down to three simple words: Evidence."    │
│ TOS: Magnifying glass icon + "EVIDENCE"                       │
│ SFX: Soft pop/reveal tone                                     │
│ Music: Light, curious, building                               │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 2.2 — Three Icons: Reasoning

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 2 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator holds up two fingers                          │
│  RIGHT: Second icon appears to the RIGHT of first:            │
│         Gear/cogs (amber/orange), label: "REASONING"          │
│         Arrow connector animates between Evidence → Reasoning │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), icons panel (right)                      │
│ Movement: Second icon slides in from right; connector draws   │
│ Duration: 0:46–0:52 (6 sec)                                   │
│ Action: Second element introduced                             │
│ Dialogue: "Reasoning."                                        │
│ TOS: Gear icon + "REASONING"                                  │
│ SFX: Click/gear sound                                         │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 2.3 — Three Icons: Action + Flow

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 2 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator holds up three fingers, then opens palm       │
│  RIGHT: Third icon appears: Forward arrow (green), "ACTION"   │
│         Full animated flow: Evidence → Reasoning → Action     │
│         connected left to right with dotted line animation.   │
│         Label above: "Data-Driven Decision Making ="          │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), full flow diagram (right)                │
│ Movement: Third icon slides in; flow line draws left to right │
│ Duration: 0:52–1:00 (8 sec)                                   │
│ Action: Full definition assembled                             │
│ Dialogue: "...and Action."                                    │
│ TOS: Full flow: Evidence + Reasoning + Action                 │
│ SFX: Final chime as flow completes                            │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design infographic three connected icons left to right: magnifying glass labeled Evidence, gear labeled Reasoning, forward arrow labeled Action, connected by dotted flow line, teal amber green palette, clean educational style",
  "width": 1248, "height": 832
}'
```

---

## Panel 2.4 — Person at Decision Tree

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 2 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator gestures to self, emphasis on "YOU"           │
│  RIGHT: Flat-design person icon at centre of small            │
│         decision tree. Branches spread to two options.        │
│         Data/charts feed into the person from the left.       │
│         Person chooses — choice arrow goes right.             │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), decision diagram (right)                 │
│ Movement: Tree branches grow outward from person              │
│ Duration: 1:00–1:08 (8 sec)                                   │
│ Action: Human as decision-maker, not data                     │
│ Dialogue: "I did not say the data decides for you."           │
│ TOS: (diagram only)                                           │
│ SFX: Branch grow sound                                        │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 2.5 — "Data Never Decides. YOU Do."

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 2 — SHOT 5                                             │
│                                                                │
│  LEFT: Narrator points directly at camera — "YOU"             │
│  RIGHT: Bold text animates in, large, centred:                │
│         "Data never decides."                                  │
│         "YOU decide —"                                        │
│         "with better information."                            │
│         Clean white on dark navy background, high contrast.   │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: CU (narrator), bold text card (right)                   │
│ Movement: Each line types/wipes in sequentially               │
│ Duration: 1:08–1:15 (7 sec)                                   │
│ Action: Core principle stated emphatically                    │
│ Dialogue: "Data never decides. You do, with better            │
│            information to guide your thinking."               │
│ TOS: "Data never decides. YOU decide — with better            │
│       information."                                           │
│ Music: Emphasised beat on "YOU"                               │
└────────────────────────────────────────────────────────────────┘
```

---

---

# SEGMENT 3 — Three Approaches [1:15–2:05]

---

## Panel 3.1 — Card 1: Intuition (Doctor)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 3 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator holds up one finger, deliberate pace          │
│  RIGHT: Character card slides in from left:                   │
│         Doctor icon with stethoscope, warm orange bg.         │
│         Label: "INTUITION"                                    │
│         Sub-label: "Experience + gut feeling"                 │
│         Strength text fades in: "Fast, powerful"              │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), character card (right)                   │
│ Movement: Card slides in from left edge                       │
│ Duration: 1:15–1:28 (13 sec)                                  │
│ Action: First approach — Intuition introduced                 │
│ Dialogue: "First: intuition. That gut feeling built from      │
│            experience. A doctor who has seen thousands of     │
│            patients looks at someone and senses something     │
│            is wrong, before any test result arrives."         │
│ TOS: Card 1 — INTUITION, "Fast, powerful"                    │
│ SFX: Card whoosh in                                           │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design character card, doctor with stethoscope, warm orange background, label Intuition below, clean educational illustration, rounded card style, no text in image",
  "width": 832, "height": 1040
}'
```

---

## Panel 3.2 — Card 2: Precedent (Manager)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 3 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator holds up two fingers                          │
│  RIGHT: Second card slides in: Manager/administrator icon,    │
│         filing cabinet or report binder, blue-grey bg.        │
│         Label: "PRECEDENT"                                    │
│         Sub: "What worked before"                             │
│         Strength: "Predictable" — Blind spot: "but limited"  │
│         Both cards now visible side by side.                  │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), two cards (right)                        │
│ Movement: Second card slides in from right                    │
│ Duration: 1:28–1:38 (10 sec)                                  │
│ Action: Second approach — Precedent introduced                │
│ Dialogue: "Second: precedent. Following what worked before.   │
│            A school uses the same exam schedule as last year  │
│            because it worked."                                │
│ TOS: Card 2 — PRECEDENT, "Predictable, but limited"          │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 3.3 — Card 3: Data-Driven (Analyst)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 3 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator holds up three fingers                        │
│  RIGHT: Third card appears: Analyst icon with bar chart,      │
│         teal/blue bg. Label: "DATA-DRIVEN"                   │
│         Sub: "Evidence + reasoning"                           │
│         All three cards now side by side, equal width.        │
│         Strength + blind spot text under each card.           │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), three cards (right)                      │
│ Movement: Third card drops in from top                        │
│ Duration: 1:38–1:50 (12 sec)                                  │
│ Action: Third approach — Data-Driven introduced               │
│ Dialogue: "Third: data-driven. A video streaming platform     │
│            suggests content based on user data..."            │
│ TOS: Card 3 — DATA-DRIVEN, "Systematic, needs good           │
│       questions"                                              │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design three character cards side by side, doctor with stethoscope, manager with filing cabinet, analyst with bar chart, clean educational illustration, orange blue teal color scheme, equal card sizes",
  "width": 1248, "height": 832
}'
```

---

## Panel 3.4 — Cards Merge: "Know When to Use Each"

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 3 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator opens both hands — "together"                 │
│  RIGHT: Three cards animate — merge/collapse into a single    │
│         unified decision-maker icon (person with lightbulb).  │
│         Text appears: "These are TOOLS, not rivals."          │
│         Sub-text: "Know when to use each."                    │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), merge animation (right)                  │
│ Movement: Cards slide to centre, merge with burst effect      │
│ Duration: 1:50–2:05 (15 sec)                                  │
│ Action: Synthesis — three tools, one decision-maker           │
│ Dialogue: "The key idea: these three are not enemies.         │
│            They are tools. Good decision-makers know when     │
│            to use each, and when to combine them."            │
│ TOS: "These are TOOLS, not rivals."                           │
│      "Know when to use each."                                 │
│ SFX: Merge/sparkle sound                                      │
│ Music: Uplifting resolution beat                              │
└────────────────────────────────────────────────────────────────┘
```

---

---

# SEGMENT 4 — Two Real-World Examples [2:05–2:50]

---

## Panel 4.1 — Example 1 Setup: District Map

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 4 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator gestures "one" — "Example one: public health" │
│  RIGHT: District map of a region. Two districts highlighted   │
│         in red. Bar chart inset: low vaccination rates.       │
│         Resource allocation arrows pointing to those          │
│         districts. Label: "More resources allocated"          │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: WS / Bird's Eye (map), MS (narrator)                    │
│ Movement: Map fades in; bars animate up; arrows draw in       │
│ Duration: 2:05–2:18 (13 sec)                                  │
│ Action: Government data decision visualised                   │
│ Dialogue: "A government programme used vaccination data to    │
│            decide which districts needed more healthcare      │
│            resources."                                        │
│ TOS: "Low vaccination rate → More resources allocated"        │
│ SFX: Map pin drop, bar grow sound                             │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 4.2 — Example 1 Reveal: Mobile Units Never Visited

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 4 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator leans forward — "But here's why..."           │
│  RIGHT: Route map overlaid: mobile van unit paths shown.      │
│         Clear GAP in the low-vaccination areas (no route      │
│         reaches them). Poor road access indicated.            │
│         Text reveal: "They were missed, not resistant."       │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: WS (map), MCU (narrator)                                │
│ Movement: Route lines draw in; gap area pulses                │
│ Duration: 2:18–2:27 (9 sec)                                   │
│ Action: Real WHY revealed — access, not refusal               │
│ Dialogue: "But in several areas, low rates were not because   │
│            people refused vaccines. Mobile van units had      │
│            simply never visited those areas."                 │
│ TOS: "They were missed, not resistant."                       │
│ SFX: Route drawing sound; gap-reveal chime                    │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design regional map with route lines showing mobile health unit paths, clear gap area with no routes reaching certain districts, red highlighted gap zone, clean infographic style, teal and red palette",
  "width": 1248, "height": 832
}'
```

---

## Panel 4.3 — Example 2 Setup: Cart Abandonment

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 4 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator holds up two fingers — "Example two"          │
│  RIGHT: E-commerce mobile screen mockup. Shopping cart icon.  │
│         Large stat: "68% cart abandonment"                    │
│         Question mark appears. Then: discount tag icon        │
│         with "Offer a discount?" label.                       │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), UI mockup (right)                        │
│ Movement: Screen slides in; stat counts up to 68%; Q mark pop │
│ Duration: 2:28–2:38 (10 sec)                                  │
│ Action: Data pattern shown; obvious (wrong) solution proposed │
│ Dialogue: "An e-commerce platform saw high cart abandonment   │
│            among women in smaller cities."                    │
│ TOS: "High cart abandonment → Offer a discount?"             │
│ SFX: Counter tick-up; question mark pop                       │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 4.4 — Example 2 Reveal: Cash on Delivery

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 4 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator shakes head — "not price, distrust"           │
│  RIGHT: Discount tag fades out. New icon: hand icon with      │
│         cash/banknotes. "Cash on Delivery" option added.      │
│         Conversion arrow turns GREEN and points upward.       │
│         Text: "No discount needed."                           │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), solution reveal (right)                  │
│ Movement: Discount fades; COD icon fades in; arrow flips      │
│ Duration: 2:38–2:43 (5 sec)                                   │
│ Action: Actual WHY = distrust of digital payment              │
│ Dialogue: "Adding cash on delivery fixed it. No discount      │
│            needed."                                           │
│ TOS: "No discount needed."                                    │
│ SFX: Cash register ding; upward arrow whoosh                  │
│ Music: Upbeat resolution                                      │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 4.5 — "Data shows WHAT. Questions reveal WHY."

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 4 — SHOT 5                                             │
│                                                                │
│  LEFT: Narrator looks directly at camera, pause for effect    │
│  RIGHT: Full-width footer text animates in across panel:      │
│         "Data shows WHAT."  (left half, teal)                 │
│         "Questions reveal WHY."  (right half, amber)          │
│         Two-column layout reinforcing the contrast.           │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), text card (right)                       │
│ Movement: Left text wipes in, then right text wipes in        │
│ Duration: 2:43–2:50 (7 sec)                                   │
│ Action: Key insight crystallised                              │
│ Dialogue: "In both cases: data showed what. Human curiosity   │
│            found out why."                                    │
│ TOS: "Data shows WHAT. Questions reveal WHY."                 │
│ SFX: Two-beat chime (one per phrase)                          │
│ Music: Thoughtful, reflective beat                            │
└────────────────────────────────────────────────────────────────┘
```

---

---

# SEGMENT 5 — Why It Matters + Honest Limits [2:50–3:35]

---

## Panel 5.1 — Benefit 1: Reduces Guessing (Piggy Bank)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator holds up one finger                           │
│  RIGHT: Piggy bank icon with ✓ checkmark, green.             │
│         Label: "Reduces costly guessing"                      │
│         Sub: "Less wasted money and effort"                   │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), benefit icon (right)                     │
│ Movement: Icon bounces in from bottom                         │
│ Duration: 2:50–2:58 (8 sec)                                   │
│ Action: Benefit 1 introduced                                  │
│ Dialogue: "One: it reduces costly guessing. Evidence-based    │
│            decisions waste less money and effort."            │
│ TOS: "✓ Reduces costly guessing"                             │
│ SFX: Checkmark tick sound                                     │
│ Music: Positive, purposeful                                   │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 5.2 — Benefit 2: Reasoning Visible (Shared Doc)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator gestures openness                             │
│  RIGHT: Document-with-checkmark icon, ✓ green.               │
│         Label: "Makes reasoning visible"                      │
│         Sub: "Accountability — others can check and improve"  │
│         First benefit still visible (smaller) beside it.      │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), two benefit icons (right)                │
│ Movement: Second icon slides in from right                    │
│ Duration: 2:58–3:07 (9 sec)                                   │
│ Action: Benefit 2 — accountability                            │
│ Dialogue: "Two: it makes your reasoning visible."             │
│ TOS: "✓ Makes reasoning visible"                             │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 5.3 — Benefit 3: Scales (Dataset Pattern)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator spreads hands wide — "scale"                  │
│  RIGHT: Grid pattern / many data points emerging from a       │
│         single person icon. ✓ green label: "Reveals patterns  │
│         at scale". All three benefit icons now visible.       │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), three benefit icons (right)              │
│ Movement: Third icon appears; data pattern grows outward      │
│ Duration: 3:07–3:15 (8 sec)                                   │
│ Action: Benefit 3 — scale                                     │
│ Dialogue: "Three: it scales. Data can reveal patterns across  │
│            thousands or millions of people."                  │
│ TOS: "✓ Reveals patterns at scale"                           │
│ Music: Brief triumphant note                                  │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design infographic three benefit icons with green checkmarks: piggy bank, shared document with tick, expanding data pattern grid, labels below each, clean educational style, green and teal palette",
  "width": 1248, "height": 832
}'
```

---

## Panel 5.4 — Transition to Limits

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator's tone shifts — pause, more serious           │
│  RIGHT: Transition graphic: benefits list slightly dims.      │
│         New heading appears: "But, honest limits:"            │
│         in amber/orange — warm warning tone.                  │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), transition card (right)                 │
│ Movement: Benefits dim 40%; new heading fades in above        │
│ Duration: 3:15–3:20 (5 sec)                                   │
│ Action: Tone shift — acknowledging limitations                │
│ Dialogue: "But Data Driven Decision Making has honest         │
│            limits too."                                       │
│ TOS: "But, honest limits:"                                    │
│ Music: Tone shifts — slightly more cautious                   │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 5.5 — Three Limits (X Icons)

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 5                                             │
│                                                                │
│  LEFT: Narrator lists each limit, one finger at a time        │
│  RIGHT: Three limit icons appear one by one, each with ✗ red: │
│         1. Puzzle with missing piece — "Can leave people out" │
│         2. Magnifying glass on wrong spot — "Can be misread"  │
│         3. Scales of justice + ? — "Cannot replace values"    │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), limit icons (right)                      │
│ Movement: Each icon pops in with red X stamp effect           │
│ Duration: 3:20–3:32 (12 sec)                                  │
│ Action: Three honest limits stated                            │
│ Dialogue: "Data can leave people out... can be misread...     │
│            cannot replace human values."                      │
│ TOS: "✗ Can leave people out / ✗ Can be misread /            │
│       ✗ Cannot replace values"                               │
│ SFX: Red stamp sound per icon                                 │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 5.6 — Both Lists Side by Side

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 5 — SHOT 6                                             │
│                                                                │
│  LEFT: Narrator, balanced tone                                │
│  RIGHT: Split layout:                                         │
│         LEFT HALF: ✓ Benefits (3 icons, green)               │
│         RIGHT HALF: ✗ Limits (3 icons, red)                  │
│         Footer text: "DDDM: powerful and limited."            │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), side-by-side summary (right)             │
│ Movement: Both columns slide to final position               │
│ Duration: 3:32–3:35 (3 sec)                                   │
│ Action: Balanced view established                             │
│ Dialogue: (visual beat, no new dialogue)                      │
│ TOS: "Data-Driven Decision Making: powerful and limited."     │
│ Music: Balanced, settled chord                                │
└────────────────────────────────────────────────────────────────┘
```

---

---

# SEGMENT 6 — Data Is Not Objective [3:35–4:35]

---

## Panel 6.1 — Myth Bubble: "DATA = OBJECTIVE TRUTH"

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 6 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator pauses deliberately — "Most important idea."  │
│  RIGHT: Large speech/thought bubble rises from bottom.        │
│         Inside: "DATA = OBJECTIVE TRUTH"                      │
│         Bubble fills screen. Holds for 1 second.              │
│         Then: bubble POPS with visible burst effect.          │
│         Fragments scatter off screen.                         │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), full-screen bubble animation (right)    │
│ Movement: Bubble floats up; POP with scatter particles        │
│ Duration: 3:35–3:48 (13 sec)                                  │
│ Action: Myth busted visually before narrator explains         │
│ Dialogue: "Data-driven does not mean objective. It does not   │
│            mean neutral or right."                            │
│ TOS: Bubble: "DATA = OBJECTIVE TRUTH" → pops                 │
│ SFX: Bubble pop (satisfying)                                  │
│ Music: Dramatic stinger on pop                                │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design large speech bubble with text DATA EQUALS OBJECTIVE TRUTH, bubble mid-pop with burst particles radiating outward, clean white background, bold typography, pop art style educational illustration",
  "width": 1248, "height": 832
}'
```

---

## Panel 6.2 — Chain Diagram: Human Choices in Data

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 6 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator counts on fingers — each stage                │
│  RIGHT: Horizontal chain, 3 stages connected by arrows:       │
│         [Person + clipboard] → "Who collects?"                │
│         [Ruler] → "What is measured?"                         │
│         [Group of people, some lit / some faded] →            │
│         "Who is included?"                                    │
│         Label below chain: "Every stage is a human choice."   │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), chain diagram (right)                    │
│ Movement: Each stage appears L→R as narrator speaks it        │
│ Duration: 3:48–4:05 (17 sec)                                  │
│ Action: Data collection as human-made process revealed        │
│ Dialogue: "Someone decided what to measure. Someone decided   │
│            who to include. Someone decided what to leave out."│
│ TOS: Chain: "Who collects? → What is measured? →             │
│       Who is included?"                                       │
│       "Every stage is a human choice."                        │
│ SFX: Arrow draw sounds, one per stage                         │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design horizontal chain diagram three stages: person with clipboard, ruler measurement icon, group of people some highlighted some greyed out, connected by arrows, label every stage is a human choice, educational infographic style",
  "width": 1248, "height": 832
}'
```

---

## Panel 6.3 — Urban School Bias Example

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 6 — SHOT 3                                             │
│                                                                │
│  LEFT: Narrator uses hands to show imbalance                  │
│  RIGHT: Bar chart of school survey results.                   │
│         Urban schools: tall bars (many, brightly coloured).   │
│         Rural schools: short bars (few, greyed out).          │
│         Large greyed-out group below the chart:               │
│         "These schools exist. The data doesn't see them."     │
│         Policy arrow points only at tall bars.                │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), bar chart (right)                        │
│ Movement: Bars grow up; grey group fades in below             │
│ Duration: 4:05–4:22 (17 sec)                                  │
│ Action: Concrete bias example — urban-heavy survey            │
│ Dialogue: "A government runs a survey to shape a new          │
│            education policy. The sample has far more urban    │
│            schools than rural ones. That leads to bias        │
│            towards urban schools."                            │
│ TOS: Bar chart imbalance; "These schools exist. The data      │
│       doesn't see them."                                      │
│ SFX: Grey group appearance — muted sound                      │
│ Music: Thoughtful, slightly unsettling undercurrent           │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 6.4 — Balance Scale: Data + Human Judgment

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 6 — SHOT 4                                             │
│                                                                │
│  LEFT: Narrator, direct and measured                          │
│  RIGHT: Balance/scales icon.                                  │
│         LEFT PAN: "Data alone" — scale tips heavily one side  │
│         RIGHT PAN: "Data + Human judgment + Critical          │
│         questions" — scale BALANCES when this side added.     │
│         Text below: "Use data. And question it."              │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), scale animation (right)                  │
│ Movement: Scale tips; then balances with satisfying settle    │
│ Duration: 4:22–4:35 (13 sec)                                  │
│ Action: Resolution — use data AND question it                 │
│ Dialogue: "Data is a powerful tool. Use it, and always ask    │
│            where it came from."                               │
│ TOS: Scale: "Data alone" ↔ "Data + Human judgment +          │
│       Critical questions"                                     │
│      "Use data. Question data."                               │
│ SFX: Scale balance settle sound                               │
│ Music: Resolving, balanced chord                              │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design balance scales, left pan labeled Data alone tipping heavy, right pan labeled Data plus Human Judgment plus Critical Questions balancing the scale, clean infographic style, teal and amber palette, educational illustration",
  "width": 1248, "height": 832
}'
```

---

---

# SEGMENT 7 — Recap + Next Up [4:35–5:00]

---

## Panel 7.1 — Checklist Ticking In

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 7 — SHOT 1                                             │
│                                                                │
│  LEFT: Narrator, warm and direct — "Quick recap."             │
│  RIGHT: Checklist animates in, items tick one by one:         │
│         ✓ DDDM = Evidence + Reasoning + Action                │
│         ✓ Three tools, not rivals                             │
│         ✓ Data has honest limits                              │
│         ✓ Data is not objective — question it                 │
│         Each item highlights as narrator says it.             │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MS (narrator), animated checklist (right)               │
│ Movement: Each item wipes in with green tick, top to bottom   │
│ Duration: 4:35–4:52 (17 sec)                                  │
│ Action: Four key takeaways recapped                           │
│ Dialogue: "Data Driven Decision Making means evidence,        │
│            reasoning, action... Intuition, precedent, and     │
│            data-driven are tools... Data has real limits...   │
│            it is never fully objective."                      │
│ TOS: ✓ DDDM = Evidence + Reasoning + Action                  │
│      ✓ Three tools, not rivals                               │
│      ✓ Data has honest limits                                │
│      ✓ Data is not objective, question it                    │
│ SFX: Tick sound per checkmark                                 │
│ Music: Warm, conclusive, building to end                      │
└────────────────────────────────────────────────────────────────┘
```

---

## Panel 7.2 — Forward Arrow to Unit 2

```
┌────────────────────────────────────────────────────────────────┐
│ SEGMENT 7 — SHOT 2                                             │
│                                                                │
│  LEFT: Narrator points forward — "Let us keep going."         │
│  RIGHT: Forward arrow icon (large, teal) appears, pointing    │
│         right. Text label: "Unit 2: The DDDM Workflow →"      │
│         Below: Progress bar:                                  │
│         [Module 1] [Unit 1 ✓] [Unit 2 →] [........]          │
│         Unit 1 segment fills green; Unit 2 pulses.            │
│                                                               │
├────────────────────────────────────────────────────────────────┤
│ Shot: MCU (narrator), forward arrow + progress bar (right)    │
│ Movement: Arrow sweeps in from left; progress bar fills       │
│ Duration: 4:52–5:00 (8 sec)                                   │
│ Action: Teaser for next unit; satisfying close                │
│ Dialogue: "In the next unit, you will learn the six-step      │
│            Data Driven Decision Making workflow — the         │
│            backbone of this entire course. Let us keep going."│
│ TOS: "Next Up: Unit 2 — The DDDM Workflow →"                 │
│      Progress bar: Unit 1 ✓ | Unit 2 →                      │
│ SFX: Progress bar fill chime                                  │
│ Music: Upbeat end sting — complete and anticipatory           │
└────────────────────────────────────────────────────────────────┘
```

**Belt prompt:**
```
belt app run falai/flux-dev-lora --input '{
  "prompt": "flat design progress bar showing module navigation, unit 1 completed green checkmark, unit 2 arrow pulsing, forward arrow icon, clean educational UI style, teal and white palette",
  "width": 1248, "height": 832
}'
```

---

---

# SHOT LIST SUMMARY

| Panel | Time | Shot | Movement | Key Visual |
|-------|------|------|----------|------------|
| 1.1 | 0:00–0:06 | MCU + Title card | Static | Title card |
| 1.2 | 0:08–0:18 | WS Bird's Eye | Map fade-in | City map + trucks |
| 1.3 | 0:08–0:18 | WS Bird's Eye | Zone highlight | North zone highlighted |
| 1.4 | 0:18–0:25 | WS Bird's Eye | Icons slide north | Staff move north |
| 1.5 | 0:25–0:32 | MCU + Counter | Counter ticks up | Red arrow, delay rising |
| 1.6 | 0:32–0:40 | MCU + Text | Text boxes pop | "Data: Correct / Question: Wrong" |
| 2.1 | 0:40–0:46 | MS + Icon | Bounce in | Magnifying glass — Evidence |
| 2.2 | 0:46–0:52 | MS + Icons | Slide in | Gear — Reasoning |
| 2.3 | 0:52–1:00 | MS + Flow | Flow draws L→R | Full DDDM flow diagram |
| 2.4 | 1:00–1:08 | MS + Diagram | Branches grow | Decision tree with person |
| 2.5 | 1:08–1:15 | CU + Text | Type-in reveal | "Data never decides. YOU do." |
| 3.1 | 1:15–1:28 | MS + Card | Slide from left | Doctor card — Intuition |
| 3.2 | 1:28–1:38 | MS + Cards | Slide from right | Manager card — Precedent |
| 3.3 | 1:38–1:50 | MS + Cards | Drop from top | Analyst card — Data-Driven |
| 3.4 | 1:50–2:05 | MS + Merge | Merge burst | Three cards → one icon |
| 4.1 | 2:05–2:18 | WS Map | Fade-in + bars | District map + vaccination bars |
| 4.2 | 2:18–2:27 | WS Map | Route draws | Mobile unit route gaps |
| 4.3 | 2:28–2:38 | MS + UI | Counter up | Cart abandonment screen |
| 4.4 | 2:38–2:43 | MS + UI | Fade swap | Cash on delivery reveal |
| 4.5 | 2:43–2:50 | MCU + Text | Split wipe | "Data shows WHAT / Questions WHY" |
| 5.1 | 2:50–2:58 | MS + Icon | Bounce in | Piggy bank ✓ |
| 5.2 | 2:58–3:07 | MS + Icons | Slide in | Doc ✓ |
| 5.3 | 3:07–3:15 | MS + Icons | Pattern grows | Scale icon ✓ |
| 5.4 | 3:15–3:20 | MCU + Transition | Dim + fade | "Honest limits:" heading |
| 5.5 | 3:20–3:32 | MS + Icons | Stamp in | Three ✗ limit icons |
| 5.6 | 3:32–3:35 | MS + Summary | Slide settle | Benefits vs Limits side by side |
| 6.1 | 3:35–3:48 | MCU + Bubble | Float + POP | Myth bubble pops |
| 6.2 | 3:48–4:05 | MS + Chain | Draw L→R | Human choices chain diagram |
| 6.3 | 4:05–4:22 | MS + Chart | Bars grow | Urban vs rural school bias |
| 6.4 | 4:22–4:35 | MS + Scale | Scale balances | Data + judgment balance |
| 7.1 | 4:35–4:52 | MS + Checklist | Tick in | 4 takeaways checklist |
| 7.2 | 4:52–5:00 | MCU + Progress | Bar fills | Unit 2 forward arrow |

---

# IMAGE GENERATION COMMANDS

Install `belt` CLI and run these to generate all key panels:

```bash
# Install belt CLI
npx skills add belt-sh/cli
belt login

# Consistent style suffix for all panels
STYLE="clean flat design educational illustration, warm professional palette, teal and amber accents, simple shapes, no text in image"

# Panel 1.2 — City map
belt app run falai/flux-dev-lora --input "{\"prompt\": \"bird eye view stylised flat design city map of Indian city, delivery truck icons scattered across districts, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 1.5 — Delay counter
belt app run falai/flux-dev-lora --input "{\"prompt\": \"dashboard delay counter rising sharply, large red upward arrow, warning indicator, concerned face icon, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 2.3 — DDDM flow diagram
belt app run falai/flux-dev-lora --input "{\"prompt\": \"three connected icons left to right: magnifying glass, gear cogs, forward arrow, connected by dotted flow line, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 3.3 — Three character cards
belt app run falai/flux-dev-lora --input "{\"prompt\": \"three character cards side by side: doctor stethoscope, manager filing cabinet, analyst bar chart, orange blue teal, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 4.2 — Route map with gaps
belt app run falai/flux-dev-lora --input "{\"prompt\": \"regional map route lines mobile health unit paths, clear gap area no routes reaching certain districts, red highlighted gap zone, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 6.1 — Myth bubble popping
belt app run falai/flux-dev-lora --input "{\"prompt\": \"large speech bubble mid-pop burst particles radiating outward, clean white background, pop art style, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait

# Panel 6.4 — Balance scale
belt app run falai/flux-dev-lora --input "{\"prompt\": \"balance scales left pan heavy tipping, right pan with multiple items balancing the scale, $STYLE\", \"width\": 1248, \"height\": 832}" --no-wait
```

---

*Storyboard for: M1_U1_1 — What is Data-Driven Decision Making?*
*Total panels: 31 | Segments: 7 | Duration: 5:00*
