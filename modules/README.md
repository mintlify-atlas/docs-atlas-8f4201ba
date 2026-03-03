# Module Documentation

This directory contains comprehensive documentation for all LiquidBounce modules, automatically generated from the source code.

## Files

- **overview.mdx** - Main overview page with all categories
- **combat.mdx** - 26 combat modules
- **movement.mdx** - 37 movement modules  
- **player.mdx** - 27 player modules
- **render.mdx** - 56 render modules
- **world.mdx** - 23 world interaction modules
- **exploit.mdx** - 25 exploit modules
- **misc.mdx** - 28 miscellaneous modules
- **fun.mdx** - 7 fun modules

## Total

**229 modules** documented across **8 categories**

## Generation

These files were automatically generated from the LiquidBounce source code by:
1. Scanning module directories
2. Extracting module names and KDoc descriptions
3. Identifying aliases and metadata
4. Generating structured MDX with Mintlify components

See `~/workspace/GENERATION_SUMMARY.md` for full details.

## Usage

Add to your `docs.json` navigation:

```json
{
  "group": "Modules",
  "pages": [
    "modules/overview",
    "modules/combat",
    "modules/movement",
    "modules/player",
    "modules/render",
    "modules/world",
    "modules/exploit",
    "modules/misc",
    "modules/fun"
  ]
}
```
