# Beamer Template

This repository contains my personal Beamer template based on the [Metropolis](https://github.com/matze/mtheme) theme by [Matthias Vogelgesang](https://github.com/matze).
It is primarily meant for my personal use at university rather than for offering a new template.


## Usage

- Adjust [variables](#variables-to-fill)
- Choose language in [`tex/header/packages.tex`](./tex/header/packages.tex)
- Replace placeholder [bibliography](./tex/bibliography.bib)
- Compile with `pdflatex`

### Variables to Fill

| Description | File(s)                                                                                                    |
|-------------|------------------------------------------------------------------------------------------------------------|
| License     | [`LICENSE`](./LICENSE)<br>[`tex/license.tex`](./tex/license.tex)<br>[`README`](./README.md#license)        |
| Metadata    | [`tex/header/metadata.tex`](./tex/header/metadata.tex)                                                     |
| Pipeline    | [`build.yaml`](./.github/workflows/build.yaml)<br>[`release.yaml`](./.github/workflows/release.yaml)       |


## License

This template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](./LICENSE) and is based on Matthias Vogelgesang's [Metropolis](https://github.com/matze/mtheme) theme.
This means that any re-distributions of it must retain the copyright notice header and the same CC-BY-SA license.
This does not affect any presentations that are created with the theme.

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width="30" /><img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width="30" /><img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width="30" />
<!-- <img src="https://mirrors.creativecommons.org/presskit/icons/nc.xlarge.png" width="30" /> -->
