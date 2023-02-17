---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Expanse Factions (EF)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- this file CC BY-ND 4.0 by zer0Kerbal -->
<!-- based upon work by Lisias -->

# Expanse Factions (EF)

[Home](./index.md)

**Flags and factions as agencies from the TV show The Expanse for Kerbal Space Program.**

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `ExpanseFactions` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ExpanseFactions`
* Extract the package's `ExpanseFactions/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/ExpanseFactions` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/ExpanseFactions`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ExpanseFactions`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/ExpanseFactions`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [ExpanseFactions]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0.txt
      * changelog.md
      * ExpanseFactions.version
      * ManualInstallation.htm
      * readme.htm
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none