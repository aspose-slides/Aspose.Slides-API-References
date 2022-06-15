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
| [FontSources](/php-java/fontsources/fontsources/)() | Creates new default font options. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getFontFolders](/php-java/fontsources/getfontfolders/)() | String | Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched. |
| [getMemoryFonts](/php-java/fontsources/getmemoryfonts/)() | byte | A collection of fonts represented as byte arrays. |
| [setFontFolders](/php-java/fontsources/setfontfolders/)(java.lang.String[]) | void | Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched. |
| [setMemoryFonts](/php-java/fontsources/setmemoryfonts/)(byte[][]) | void | A collection of fonts represented as byte arrays. |
