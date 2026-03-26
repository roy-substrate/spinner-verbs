# Claude Code Spinner Verbs

All **185 built-in spinner verbs** that Claude Code displays while processing your requests. These are the whimsical loading messages that cycle in your terminal while Claude thinks.

> *"Frolicking… Waddling… Discombobulating…"*
> These aren't random — they're a curated vocabulary of gerunds displayed by Claude Code while it works.

Last verified on **Claude Code v2.1.42** (February 2026).

---

## The Complete List

### A
Accomplishing · Actioning · Actualizing · Architecting

### B
Baking · Beaming · Beboppin' · Befuddling · Billowing · Blanching · Bloviating · Boogieing · Boondoggling · Booping · Bootstrapping · Brewing · Burrowing

### C
Calculating · Canoodling · Caramelizing · Cascading · Catapulting · Cerebrating · Channeling · Channelling · Choreographing · Churning · Clauding · Coalescing · Cogitating · Combobulating · Composing · Computing · Concocting · Considering · Contemplating · Cooking · Crafting · Creating · Crunching · Crystallizing · Cultivating

### D
Deciphering · Deliberating · Determining · Dilly-dallying · Discombobulating · Doing · Doodling · Drizzling

### E
Ebbing · Effecting · Elucidating · Embellishing · Enchanting · Envisioning · Evaporating

### F
Fermenting · Fiddle-faddling · Finagling · Flambéing · Flibbertigibbeting · Flowing · Flummoxing · Fluttering · Forging · Forming · Frolicking · Frosting

### G
Gallivanting · Galloping · Garnishing · Generating · Germinating · Gitifying · Grooving · Gusting

### H
Harmonizing · Hashing · Hatching · Herding · Honking · Hullaballooing · Hyperspacing

### I
Ideating · Imagining · Improvising · Incubating · Inferring · Infusing · Ionizing

### J
Jitterbugging · Julienning

### K
Kneading

### L
Leavening · Levitating · Lollygagging

### M
Manifesting · Marinating · Meandering · Metamorphosing · Misting · Moonwalking · Moseying · Mulling · Musing · Mustering

### N
Nebulizing · Nesting · Newspapering · Noodling · Nucleating

### O
Orbiting · Orchestrating · Osmosing

### P
Perambulating · Percolating · Perusing · Philosophising · Photosynthesizing · Pollinating · Pondering · Pontificating · Pouncing · Precipitating · Prestidigitating · Processing · Proofing · Propagating · Puttering · Puzzling

### Q
Quantumizing

### R
Razzle-dazzling · Razzmatazzing · Recombobulating · Reticulating · Roosting · Ruminating

### S
Sautéing · Scampering · Schlepping · Scurrying · Seasoning · Shenaniganing · Shimmying · Simmering · Skedaddling · Sketching · Slithering · Smooshing · Sock-hopping · Spelunking · Spinning · Sprouting · Stewing · Sublimating · Swirling · Swooping · Symbioting · Synthesizing

### T
Tempering · Thinking · Thundering · Tinkering · Tomfoolering · Topsy-turvying · Transfiguring · Transmuting · Twisting

### U
Undulating · Unfurling · Unravelling

### V
Vibing

### W
Waddling · Wandering · Warping · Whatchamacalliting · Whirlpooling · Whirring · Whisking · Wibbling · Working · Wrangling

### Z
Zesting · Zigzagging

---

## By Category

| Category | Count | Examples |
|----------|-------|---------|
| 🍳 Culinary | 22 | Baking, Caramelizing, Flambéing, Julienning, Sautéing |
| 🧠 Cerebral | 22 | Cerebrating, Cogitating, Contemplating, Pondering, Ruminating |
| 🎪 Whimsical | 30 | Booping, Clauding, Discombobulating, Flibbertigibbeting, Whatchamacalliting |
| 🏃 Kinetic | 28 | Frolicking, Gallivanting, Moonwalking, Skedaddling, Spelunking |
| 🌿 Nature | 16 | Billowing, Germinating, Pollinating, Sprouting, Undulating |
| 🔨 Craft | 16 | Architecting, Choreographing, Composing, Forging, Orchestrating |
| 🔬 Science | 16 | Crystallizing, Ionizing, Metamorphosing, Quantumizing, Sublimating |
| ⚙️ General | 15 | Accomplishing, Computing, Doing, Processing, Working |

---

## Version History

| Era | Versions | Verbs Added | Highlights |
|-----|----------|-------------|------------|
| Primordial | v0.2.9 – v0.2.41 | 56 | The originals: Computing, Processing, Noodling, Honking, Vibing |
| Singular Addition | v0.2.42 | 1 | Pontificating arrived with appropriate ceremony |
| Great Expansion | v1.0.29 | 33 | Flibbertigibbeting, Discombobulating, Wizarding — tone shifts to whimsy |
| Modern Era | v1.0.49+ | 95 | Culinary arts, dance moves, science terms, and the inexplicable |

---

## Customization

Since **v2.1.23** (January 2026), you can customize spinner verbs in `~/.claude/settings.json`:

### Replace all defaults
```json
{
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": [
      "Your-verb-here",
      "Another-verb-here"
    ]
  }
}
```

### Add to defaults
```json
{
  "spinnerVerbs": {
    "mode": "append",
    "verbs": [
      "Your-extra-verb",
      "Another-extra-verb"
    ]
  }
}
```

**Tips:**
- Use present participles (ending in `-ing`)
- Keep them short so they render cleanly in the terminal
- Use `replace` for full control, `append` to mix with the built-in 185

---

## Fun Facts

- **"Clauding"** is the only self-referential verb — Claude Code literally says it's *Clauding*
- **"Flibbertigibbeting"** at 19 characters is among the longest single-word verbs
- **"Doing"** is the most understated verb in the entire collection
- **"Recombobulating"** exists alongside both **"Combobulating"** and **"Discombobulating"** — covering the full spectrum
- The internal codename for Claude Code is **"Tengu"** (天狗) — supernatural beings from Japanese folklore known for cleverness and shape-shifting

---

## Contributing

Found a new verb in a recent version? Open an issue or PR!

## License

This is a community reference document. Claude Code is a product of [Anthropic](https://anthropic.com).
