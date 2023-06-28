# Floorball rules but machine-readable

This repo contains floorball rules in a machine-readable JSON format. They are extracted from the original PDF on [IFF's page](https://floorball.sport/rules-and-regulations/rules-of-the-game/) semi-manually by copy-pasting from the PDF into .txt files in the `raw/` directory, and then using the `extract_rules.ipynb` notebook to parse this into JSON files.

Structure of the final data:
* `rules.json` -- main body text of rules.
* `glossary.json` -- main terms used in the rules
* `signs.json` -- metadata of hand signs
* `figures/signs/*.png` -- illustrations of hand signs
* `figures/{rink,goalkeeper_area}.png` -- rink diagrams present in the official rules

You can use this however you want (see LICENSE.md) but I would appreciate a reference to this repository.
