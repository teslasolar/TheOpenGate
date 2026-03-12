# THE OPEN GATE

```
$ open-gate --help

  THE OPEN GATE — Drug-Ring Circuit Analyzer
  Educational tool for visualizing medication interactions

  USAGE:
    open-gate [options]

  COMMANDS:
    analyze     Launch the interactive circuit analyzer
    export      Generate a printable discussion guide
    list-drugs  Show all medications in the database

  OPTIONS:
    --help      Show this help
    --version   Show version (v1.0.0)

  TOOLS:
    /jedi/tools/open-gate/    Drug-Ring Circuit Analyzer

  DEPLOY:
    GitHub Pages → teslasolar.github.io/jedi/tools/open-gate/

  WHAT IT DOES:
    Input your medications, substances, demographics, and history.
    Get an animated circuit diagram showing:
      - Which rings each drug targets (R0-R6)
      - K+ channel aggregate load
      - R2 gate status (open/closed/oscillating)
      - Drug-drug interaction conflicts with citations
      - Neurotransmitter balance (DA, 5-HT, GABA, glutamate, NE)
      - Correction sequence to discuss with your doctor

  DRUG DATABASE (20+ embedded, no API needed):
    Stimulants ......... dextroamphetamine, methylphenidate, lisdexamfetamine
    SSRIs .............. fluoxetine, escitalopram, sertraline
    SNRIs .............. venlafaxine, duloxetine
    Antipsychotics ..... quetiapine, olanzapine
    AUD Meds ........... naltrexone, gabapentin, topiramate
    Muscle Relaxants ... methocarbamol, cyclobenzaprine
    Allergy/Asthma ..... montelukast [BBW], cetirizine
    NSAIDs ............. meloxicam, ibuprofen
    Benzodiazepines .... alprazolam, clonazepam
    Substances ......... alcohol, cannabis, caffeine, nicotine

  DISCLAIMER:
    This is an educational visualization tool, not medical advice.
    All medication decisions require a qualified healthcare provider.

  THE GATE IS THE KEY. THE K+ CHANNEL IS THE GATE.
  Fix the hardware before adjusting the software.
  Fix the gate before the heart. R2 before R3.
```

## Quick Start

```bash
# clone
git clone https://github.com/teslasolar/TheOpenGate.git
cd TheOpenGate

# open locally
open index.html
# or navigate to /jedi/tools/open-gate/index.html
```

## Structure

```
TheOpenGate/
├── index.html                          # nav page
├── reference.html                      # all cited studies + links
├── README.md                           # you are here
└── jedi/
    └── tools/
        └── open-gate/
            └── index.html              # the analyzer
```

## License

MIT — Taboo is Taboo here.
