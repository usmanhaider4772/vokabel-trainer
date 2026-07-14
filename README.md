# Vokabeltrainer

A phone-friendly German flashcard app with three quiz modes and a DE↔EN direction toggle.

## Files

| File | What it is |
|---|---|
| `vokabeltrainer.html` | The app — open it in any browser, works fully offline |
| `word_meaning.csv` | 180 nouns: word, meaning, plural, example |
| `verb_perfekt.csv` | 146 verbs: infinitive, Perfekt, meaning |
| `verb_praeteritum.csv` | 146 verbs: infinitive, Präteritum, meaning |
| `verb_meaning.csv` | 146 verbs: infinitive, meaning only |

The CSVs are for reference — the app already has this data built in.

## Modes

- **Wort–Bedeutung** — 180 nouns across everyday topics (family, home, food, animals, body, clothing, nature, time, places, jobs, transport, school, abstract words). Flipping a card also reveals the **plural form** (or "kein Plural" if it has none).
- **Verb–Perfekt** — 146 verbs with their Perfekt form (`hat/ist` + participle).
- **Verb–Präteritum** — the same 146 verbs with their simple-past form.

## How to use it

1. Tap the card (or press **Space**/**Enter**) to flip it.
2. Mark **✓ Kann ich** if you knew it, or **↺ Nochmal** to see it again later in the round — missed cards get reshuffled back in.
3. Swipe right = knew it, swipe left = again (once the card is flipped).
4. Use the **⇄ direction toggle** to quiz yourself the other way (e.g. EN → DE, or Perfekt → Infinitiv).
5. Switch modes anytime with the tabs at the top.

## Adding more vocabulary

Send new word lists or images and I'll extend the datasets built into `vokabeltrainer.html` directly — no manual import needed.
