---
title: FontsLoader
type: docs
weight: 0
url: /php-java/fontsloader/
---

# FontsLoader class

 Class for loading custom fonts defined by user.
 Should be used before creating any presentation objects.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [clearCache](/slides/php-java/fontsloader/clearcache/)() | void | Releases all custom fonts defined by user This method needs to clear cache with custom fonts defined by user. |
| [getFontFolders](/slides/php-java/fontsloader/getfontfolders/)() | String | Gets font folders. Returns folders that have been added with LoadExternalFonts method as well as system font folders |
| [loadExternalFont](/slides/php-java/fontsloader/loadexternalfont/)(byte[]) | void | Adds font from the binary data |
| [loadExternalFonts](/slides/php-java/fontsloader/loadexternalfonts/)(java.lang.String[]) | void | Adds additional folders to seek fonts. |
