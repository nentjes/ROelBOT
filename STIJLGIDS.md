# Nentjes Stijlgids

De huisstijl voor al je sites — afgeleid van **ROelBOT** (roelbot.nentjes.nl), in de
look & feel van **DeLocatieManager**. Twee delen: de **stem** (hoe je schrijft) en de
**look & feel** (hoe het eruitziet). Alles is copy-paste-klaar.

Kernidee: *Apple-rustig en zakelijk, met ervaring en kwetsbaarheid die er subtiel
doorheen schemeren.*

---

## DEEL 1 — DE STEM (schrijfstijl)

### De vijf principes

1. **Zakelijk als basis.** Professioneel, helder, geen poespas. Maar nooit kil.
2. **Geen "ik".** Vermijd `ik`, `mijn`, `mij`. Gebruik de merknaam, "we", of een
   onpersoonlijke constructie. Dit voorkomt de toon van "ik heb de waarheid in pacht".
3. **Vragen, niet preken.** Verwonder je, stel vragen, nodig uit. Koppen mogen vragen
   zijn. Liever "Wat als…", "Misschien…", "Zullen we…" dan stellige beweringen.
4. **Laat ervaring schemeren.** Niet opscheppen, wél een doorgewinterde blik laten
   voelen — en spaarzaam. Eén of twee subtiele signalen per pagina, niet om de zin.
5. **Laat kwetsbaarheid schemeren.** Durf te zeggen dat niet alles zeker is. Geen
   indek-clausules of disclaimers, maar eerlijke openheid.

### Geen "ik" — zo doe je dat

| In plaats van (te stellig, te persoonlijk) | Schrijf (zakelijk, vragend) |
| --- | --- |
| "Ik verbind strategie, robotica en IT." | "Geen kant-en-klare antwoorden — wel de overtuiging dat het anders moet." |
| "Ik stap in het gat tussen partijen." | "Misschien ligt de oplossing juist in dat gat." |
| "Ik voer de IT-governance en regel alles." | "Samen met de IT-partij ontstaat een manier om het veilig te laten draaien." |
| "Ik probeer de brug te zijn." | "De brug tussen wat het bestuur wil en wat de techniek kan." |

### Koppen als vraag, niet als oordeel

| Niet | Wel |
| --- | --- |
| "De zorg heeft haar eigen IT wegbezuinigd." | "Hebben we de innovatie mee uitbesteed?" |
| "Vraag een strategische verkenning aan." | "Zullen we eens praten?" |
| "Dit is dé oplossing." | "Wat als het anders kan?" |

### Ervaring laten schemeren (subtiel, onpersoonlijk)

- "Twintig jaar praktijk in de zorg leert dat de techniek zelden het echte struikelblok is."
- "Wie lang genoeg meeloopt, herkent het patroon."
- "Na jaren tussen bestuur, leverancier en IT…"
- "Waar jarenlange ervaring met zorgnetwerken het meest van pas komt."

> Vuistregel: hooguit 1–2 van dit soort signalen per pagina. Schemeren, niet schreeuwen.
> En nooit het letterlijke "20 jaar ervaring" als slogan herhalen.

### Kwetsbaarheid laten schemeren

- "Geen kant-en-klare antwoorden — wel de overtuiging dat het anders moet."
- "Soms is het antwoord nee — en dan is dát het advies."
- "Niet vanuit alwetendheid, maar vanuit de juiste vragen."
- "Waar het toe leidt is op voorhand niet te zeggen, en juist dat maakt het de moeite waard."

### Rode draad & uitnodiging

Gebruik deze gedachte als kloppend hart van een site:

> *Als we blijven doen wat we deden, houden we wat we hadden.*

En nodig uit in plaats van te verkopen:
- "ROelBOT zoekt bestuurders die dat durven onderzoeken."
- "Dan is dit een uitnodiging. Niet om iets te verkopen — wel om samen te kijken of het anders kan."

### Aanspreekvorm & microcopy

- **"je"** voor warmte en ooghoogte in lopende tekst; neutraal/onpersoonlijk waar het zakelijker mag.
- **Knoppen**: kort en concreet — "Boek een scan", "Verstuur bericht", "Ontdek de 13 use cases".
- **Bevestigingen**: menselijk en zonder "ik" — *"Dank {naam}, het bericht is binnen. Je hoort snel persoonlijk iets terug."*
- **Geen** angst-microcopy onder knoppen ("zonder verplichtingen", "we spammen niet"). Vertrouwen i.p.v. indekken.

### Niet doen

- Geen "ik / mijn / mij".
- Geen salespraat, superlatieven of buzzword-stapeling ("revolutionair", "dé oplossing", "naadloos disruptief").
- Geen disclaimers of indek-clausules.
- Geen jargon zonder mensentaal erbij (technische termen mogen — NEN 7510, VLAN — maar leg ze uit).

---

## DEEL 2 — DE LOOK & FEEL (visueel)

Apple/macOS-design: systeemfont, lichtgrijze achtergrond, witte kaarten, zachte
schaduwen, veel witruimte. Rustig en hoogwaardig.

### Kleuren

| Rol | Variabele | Waarde |
| --- | --- | --- |
| Pagina-achtergrond | `--gray-100` | `#F2F2F7` |
| Kaart / wit vlak | `--bg` | `#FFFFFF` |
| Tekst primair | `--text` | `#000000` |
| Tekst secundair | `--text-secondary` | `#3C3C43` |
| Tekst tertiair / labels | `--text-tertiary` | `#8E8E93` |
| **Actie & links (blauw)** | `--blue` | `#007AFF` |
| Actie hover | `--blue-dark` | `#0062CC` |
| **Merkkleur (groen, icoon/gradient)** | `--green-brand-1 → 2` | `#43A047` → `#2E7D32` |
| Groen tekst / positief | `--green-text` | `#1B7A3D` |
| Systeemgroen (accenten) | `--green` | `#34C759` |
| Rood / negatief | `--red` | `#FF3B30` |
| Rood tekst | `--red-text` | `#C0392B` |
| Scheidingslijn | `--separator` | `rgba(60,60,67,0.12)` |

**Kleurlogica (belangrijk):**
- **Blauw = interactie** — knoppen, links, actieve staat. Niet decoratief gebruiken.
- **Groen = identiteit** — het logo-icoon, de merkaccenten, positieve labels.
- **Rood vs. groen = betekenis** — gebruik ze semantisch (probleem vs. oplossing), niet voor sier.
- Verder: zwart, wit en grijs. **Geen oranje/amber/bruin** — die voelen kinderachtig, niet premium.

### Typografie

- **Lettertype:** het systeemfont, geen webfont.
  `font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "SF Pro Display", "Helvetica Neue", Arial, sans-serif;`
  met `-webkit-font-smoothing: antialiased;`
- **Basis:** 16px, regelhoogte 1.5.
- **Koppen:** vet (700), strakke letterspacing `-0.025em` (hero `-0.035em`).
- **Accent in koppen:** kleur één deel groen (`--green-brand-2`), bijv. een sleutelwoord.

### Ruimte, hoeken, schaduw

- **Hoeken:** knoppen `10px`, kaarten `12–16px` (`--radius` / `--radius-lg`).
- **Schaduw (subtiel!):**
  `--card-shadow: 0 0.5px 0 0 rgba(0,0,0,0.04), 0 1px 3px rgba(0,0,0,0.06);`
  hover: `0 4px 18px rgba(0,0,0,0.09);`
- **Witruimte:** royaal. Secties ~84px verticaal, container `max-width: 1200px`, padding 24px.
- **Lijnen i.p.v. dozen:** scheid met haarlijnen (`0.5px solid var(--separator)`) waar een kaart te zwaar zou zijn.

### Het logo

- **Icoon:** afgerond vierkant (`8px`) met groen verloop (`135deg, #43A047 → #2E7D32`),
  witte beginletter, vetgedrukt.
- **Woordmerk-regel:** de letters die samen een herkenbaar woord vormen in **zwart**,
  het ingevoegde tussenstuk in **groen**. Bij ROelBOT: `RO` + **`el`** (groen) + `BOT`
  → zo schemert het woord "ROBOT" door de naam. Pas dezelfde logica toe op andere namen.

### Componenten

**Accentlijn (bovenaan, 3px):**
```css
.accent-line {
  position: fixed; top: 0; left: 0; right: 0; height: 3px; z-index: 101;
  background: linear-gradient(90deg, #007AFF, #5AC8FA, #34C759, #AF52DE);
}
```

**Topbar (glasmorfisme):**
```css
.topbar {
  position: fixed; top: 3px; left: 0; right: 0; z-index: 100;
  background: rgba(255,255,255,0.72);
  backdrop-filter: saturate(180%) blur(20px);
  -webkit-backdrop-filter: saturate(180%) blur(20px);
  border-bottom: 0.5px solid var(--separator);
}
```

**Knoppen:**
```css
.btn { display:inline-flex; align-items:center; gap:8px; cursor:pointer; border:0;
  font: inherit; font-size:15px; font-weight:600; padding:10px 18px; border-radius:10px;
  transition: background .15s, box-shadow .15s; }
.btn-primary { background: var(--blue); color:#fff; }      /* primaire actie = blauw */
.btn-primary:hover { background: var(--blue-dark); }
.btn-ghost { background: var(--bg); color: var(--text); box-shadow: var(--card-shadow); }
```

**Kaart met rijen (de signatuur — voor heldere informatie):**
```css
.apple-card { background: var(--bg); border-radius: var(--radius);
  box-shadow: var(--card-shadow); overflow:hidden; }
.apple-card-row { display:flex; align-items:flex-start; gap:16px; padding:14px 18px;
  border-bottom: 0.5px solid var(--separator); }
.apple-card-row:last-child { border-bottom:none; }
.apple-card-label { font-size:13px; font-weight:600; color:var(--text); min-width:150px; flex-shrink:0; }
.apple-card-value { font-size:14px; color:var(--text-secondary); flex:1; line-height:1.5; }
```
```html
<div class="apple-card">
  <div class="apple-card-row">
    <div class="apple-card-label">Label</div>
    <div class="apple-card-value">Heldere uitleg in mensentaal.</div>
  </div>
</div>
```

**Zachte status-badges (voor categorieën/sectoren):**
```css
.badge { font-size:12px; font-weight:600; padding:4px 10px; border-radius:8px; }
.badge-blue  { background:#E7F0FF; color:#0B5BD3; }
.badge-green { background:#E6F7EC; color:#1B7A3D; }
.badge-purple{ background:#EEE9FB; color:#6B3FBF; }
```

**Kicker (klein label boven een kop):**
```css
.kicker { display:inline-flex; align-items:center; gap:8px; font-size:13px; font-weight:600;
  letter-spacing:.02em; text-transform:uppercase; color:var(--green-text); }
.kicker::before { content:''; width:22px; height:2px; border-radius:2px; background:var(--green-brand-1); }
```

**Segmented filter (Apple-stijl tabs):**
```css
.seg { display:inline-flex; background:var(--gray-100); border-radius:11px; padding:3px; gap:2px; }
.seg button { border:0; background:transparent; font:inherit; font-size:14px; font-weight:600;
  color:var(--text-tertiary); padding:8px 16px; border-radius:8px; cursor:pointer; }
.seg button.active { background:var(--bg); color:var(--text); box-shadow:var(--card-shadow); }
```

### Responsive & techniek

- **Mobile-first**, breekpunt rond `900px` (nav → hamburger), kaartgrids vallen terug naar 1 kolom rond `720px`.
- **Geen Tailwind-CDN, geen webfont**: pure CSS met `:root`-variabelen en het systeemfont.
  Sneller, betrouwbaarder, en rendert ook zonder internet.
- **Toegankelijkheid:** voldoende contrast (zwart op wit/lichtgrijs), `:focus` met een
  blauwe ring (`box-shadow: 0 0 0 3px rgba(0,122,255,0.2)`), echte `<button>`/`<a>`-elementen.

---

## DEEL 3 — SNELSTART (copy-paste basis)

Plak dit bovenaan je stylesheet en je hebt direct de juiste basis:

```css
:root {
  --blue:#007AFF; --blue-dark:#0062CC; --blue-light:rgba(0,122,255,0.08);
  --green:#34C759; --green-brand-1:#43A047; --green-brand-2:#2E7D32; --green-text:#1B7A3D; --green-light:rgba(52,199,89,0.10);
  --red:#FF3B30; --red-text:#C0392B; --red-light:rgba(255,59,48,0.07);
  --gray-100:#F2F2F7; --gray-200:#E5E5EA; --gray-300:#D1D1D6;
  --text:#000000; --text-secondary:#3C3C43; --text-tertiary:#8E8E93;
  --bg:#FFFFFF; --separator:rgba(60,60,67,0.12);
  --card-shadow:0 0.5px 0 0 rgba(0,0,0,0.04), 0 1px 3px rgba(0,0,0,0.06);
  --card-shadow-hover:0 4px 18px rgba(0,0,0,0.09);
  --radius:12px; --radius-lg:16px;
}
*, *::before, *::after { box-sizing:border-box; margin:0; padding:0; }
html { font-family:-apple-system, BlinkMacSystemFont,"SF Pro Text","SF Pro Display","Helvetica Neue",Arial,sans-serif;
  -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;
  background:var(--gray-100); color:var(--text); font-size:16px; line-height:1.5; scroll-behavior:smooth; }
a { color:inherit; text-decoration:none; }
.wrap { max-width:1200px; margin:0 auto; padding:0 24px; }
.section { padding:84px 0; }
```

---

## CHECKLIST — voor elke nieuwe pagina

**Tekst**
- [ ] Nergens "ik / mijn / mij".
- [ ] Minstens één kop is een vraag.
- [ ] Eén of twee subtiele ervaring-signalen (niet meer).
- [ ] Eén eerlijke, kwetsbare zin (geen indek-clausule).
- [ ] Geen salespraat of disclaimers onder knoppen.
- [ ] Technische termen uitgelegd in mensentaal.

**Beeld**
- [ ] Achtergrond `#F2F2F7`, witte kaarten, subtiele schaduw.
- [ ] Systeemfont, geen webfont; strakke letterspacing op koppen.
- [ ] Blauw alleen voor acties/links; groen voor merk; rood/groen alleen semantisch.
- [ ] Geen oranje/amber/bruin.
- [ ] Logo: woord-letters zwart, ingevoegd tussenstuk groen.
- [ ] Royale witruimte, haarlijnen waar een kaart te zwaar zou zijn.
