# KiCad Symbols + Footprints

In your KiCad project, clone this repo as a submodule.

```bash
# In your project directory with a .kicad_pro file:
git submodule add git@github.com:ucb-bar/kicad-parts.git
```

Then, in the KiCad project GUI, add `kicad-parts/kicad-parts.kicad_sym` as a project-specific symbol library and `kicad-parts/kicad-parts.pretty` as a project-specific footprint library.
