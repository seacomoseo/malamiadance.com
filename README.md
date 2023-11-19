# malamiadance.com

[![malamiadance.com](/assets/media/logo.png)](https://malamiadance.com/)
- [![Netlify Status](https://api.netlify.com/api/v1/badges/a18a7c86-2778-4058-8494-ca71226980e6/deploy-status)](https://app.netlify.com/sites/malamia/deploys)


## STEPS

### Local

- Design
  - FONTS
    - Fonts that not be in Google Fonts:
      - .otf/.ttf files in `assets/fonts` + rename
      - You need the `malamia_tools` proyect in `../_tools` folder
      - Run `make fonts` comand
      - `Family` + `Style` + `Weight` must match in `config.yml ⏩ params.fonts` + `_fonts.scss` (and disable `params.fonts.google_fonts` if appropriate)
  - Try in Safari and Firefox