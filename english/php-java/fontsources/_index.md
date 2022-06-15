---
title: FontSources
type: docs
weight: 0
url: /php-java/fontsources/
---

# FontSources class

 Provides file and memory sources for external fonts.
 

## Constructors

| name | description |
| --- | --- |
| [FontSources](/slides/php-java/fontsources/fontsources/)() | Creates new default font options. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getFontFolders](/slides/php-java/fontsources/getfontfolders/)() | String | Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched. |
| [getMemoryFonts](/slides/php-java/fontsources/getmemoryfonts/)() | byte | A collection of fonts represented as byte arrays. |
| [setFontFolders](/slides/php-java/fontsources/setfontfolders/)(java.lang.String[]) | void | Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched. |
| [setMemoryFonts](/slides/php-java/fontsources/setmemoryfonts/)(byte[][]) | void | A collection of fonts represented as byte arrays. |
