---
license: cc-by-4.0
language:
  - en
pretty_name: WorkChoose Workspace Equipment Comparison Data
tags:
  - home-office
  - ergonomics
  - product-comparison
  - walking-pads
  - standing-desks
  - portable-monitors
---

# WorkChoose Workspace Equipment Comparison Data

Source-backed comparison tables for screening the physical and technical fit of walking pads, standing desks, and portable monitors. The data is maintained by [WorkChoose](https://workchoose.com/data) and is intended for research, comparison, and pre-purchase measurement—not as a substitute for a current manufacturer listing, manual, or safety instruction.

## Files

| File                                   | Rows | What it covers                                                                                                            |
| -------------------------------------- | ---: | ------------------------------------------------------------------------------------------------------------------------- |
| `walking-pad-comparison-data.csv`      |   19 | Outside and belt dimensions, speed, published load, machine weight, folding, controls, official sources, and caveats      |
| `standing-desk-comparison-data.csv`    |    9 | Finished/frame height, desktop range, frame geometry, motors, published load labels, official sources, and related guides |
| `portable-monitor-comparison-data.csv` |    9 | Display, inputs, power path, physical setup, touch, Mac/iPad notes, official sources, and related guides                  |

## Evidence and collection method

- Values were manually transcribed and normalized from the official product pages, manuals, specification sheets, warranty pages, return pages, and support documents named in each row.
- `checked_on` records the review date where the dataset provides it. Product availability, variants, specifications, and policies can change after that date.
- Manufacturer statements are retained as published evidence. They are not WorkChoose laboratory measurements or hands-on test results.
- Missing or conflicting evidence is kept visible as `Unknown` or explained in a caveat instead of being guessed.
- US product variants and US customary units are the primary scope. Do not silently apply a row to another regional variant.

## Important limitations

The files do not prove delivered fit, comfort, durability, noise, stability, image quality, cable behavior, medical benefit, or safe operation. A connector name does not prove video or power compatibility. A published load label does not prove high-position desk stability. A machine's outside height is not automatically its standing-surface height. Follow the current manufacturer documentation and perform your own measurement before purchase or use.

## Suggested citation

> WorkChoose. _WorkChoose Workspace Equipment Comparison Data — 2026-09_. September 2026. https://workchoose.com/data

When citing an individual value, link to the exact WorkChoose data page or CSV and preserve the relevant source and caveat fields.

## License

The structured comparison data and original field organization are available under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). See `data-license.txt` for attribution guidance and exclusions. Manufacturer names, trademarks, linked documents, and third-party content remain the property of their respective owners.

## Related interactive tools

- [Home office layout calculator](https://workchoose.com/home-office-layout-calculator)
- [Walking-pad comparison chart](https://workchoose.com/walking-pad-comparison-chart)
- [Standing-desk comparison chart](https://workchoose.com/standing-desk-comparison-chart)
- [Portable-monitor comparison chart](https://workchoose.com/portable-monitor-comparison-chart)
- [Walking-pad desk-height calculator](https://workchoose.com/walking-pad-desk-height-clearance)
- [Portable-monitor connection checker](https://workchoose.com/portable-monitor-connection-checker)

## Arzopa portable-monitor buyer guides

The portable-monitor dataset now includes five current Arzopa models with direct manufacturer evidence. These independent decision pages explain the tradeoffs without claiming hands-on testing:

- [Best Arzopa portable monitor: five models compared](https://workchoose.com/best-arzopa-portable-monitor)
- [Arzopa Z3FC vs Z1RC: gaming or 16:10 work](https://workchoose.com/arzopa-z3fc-vs-z1rc)
- [Arzopa Z3FC review](https://workchoose.com/arzopa-z3fc-review)
- [Arzopa Z1RC review](https://workchoose.com/arzopa-z1rc-review)

## Free embeddable tools

Publishers can add either calculator to a relevant article with one script tag
or a plain iframe. The widgets are free, require no login, use isolated styles,
and do not save a visitor's measurements.

- [Embed the walking-pad desk-fit calculator](https://workchoose.com/embed-desk-fit-calculator)
- [Embed the portable-monitor connection checker](https://workchoose.com/embed-portable-monitor-checker)

Corrections and dataset-use questions: [contact WorkChoose](https://workchoose.com/contact).
