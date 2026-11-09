# Leina Themes

Downloadable themes for Leina Player (Ustawienia > Wygląd > Pobierz motyw).

- `index.json` lists the themes the app's browser shows.
- `themes/<id>/theme.json` is a theme; fonts and their licence sit next to it.

A theme is only data: colours (`#RRGGBB` or `#AARRGGBB`), a few look switches (`rounded`,
`chamfered`, `panelHeaders`, `uppercaseTitles`) and a font. Raise `version` in both files on
every change, so phones offer the update. `format` is the file format; an app that does not know
it leaves the theme out.

The Rajdhani font in `themes/Cyberpunk/` is under the SIL Open Font License 1.1 (`OFL.txt` there).
