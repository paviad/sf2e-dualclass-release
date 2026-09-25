# SF2e Dual Classing — releases

Release packages of the **SF2e Dual Classing** Foundry VTT module, which adds the
Pathfinder 2e Dual-Class variant rule to the Starfinder 2e system (first class
Starfinder, second class Pathfinder).

This repository holds releases only; there is no source here.

## Install

In Foundry's **Setup** screen → **Add-on Modules** → **Install Module**, paste
this into *Manifest URL*:

```
https://github.com/paviad/sf2e-dualclass-release/releases/latest/download/module.json
```

Updates then appear in the Add-on Modules list — click **Update**.

## Get notified of new versions

Foundry only shows an update when you open the Setup screen. To hear about one
as soon as it is published:

- **Email and phone:** on this page click **Watch** → **Custom** → tick
  **Releases** → **Apply** (needs a free GitHub account). GitHub emails you for
  every release, and the GitHub mobile app sends a push notification.
- **RSS, no account:** subscribe to
  `https://github.com/paviad/sf2e-dualclass-release/releases.atom` in any feed
  reader.

## Keeping up to date

Updating this module does **not** update the game system or Pathfinder
Anachronism — Foundry updates each package separately. When you update, use
**Update All** on both the **Game Systems** and **Add-on Modules** tabs, then
relaunch the world.

If either is older than the version this module was tested with, the module
says so in a warning when the world loads, and keeps working. Some updates also
repair character data: if any character needs it, the world opens with an
*Update character data* dialog that lists every change before making it. Back
up the world first.

## Requirements

- Foundry VTT **v14**
- Game system **Starfinder 2e** (`sf2e`)
- Module **Pathfinder Anachronism** (`pf2e-anachronism`), for the Pathfinder classes:
  `https://raw.githubusercontent.com/foundryvtt/pf2e/v14-dev/module.pf2e-anachronism.json`
