---
title: FontsLoader
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/fontsloader/
---

## FontsLoader class

 Class for loading custom fonts defined by user.
 Should be used before creating any presentation objects.
 
### clearCache {#clearCache}

| Name | Description |
| --- | --- |
| clearCache () | Releases all custom fonts defined by user This function needs to clear cache with custom fonts defined by user. |


---


### getFontFolders {#getFontFolders}

| Name | Description |
| --- | --- |
| getFontFolders () | Gets font folders. Returns folders that have been added with LoadExternalFonts function as well as system font folders |

 **Result**
String


---


### loadExternalFont {#loadExternalFont}

| Name | Description |
| --- | --- |
| loadExternalFont (byte[]) | Adds font from the binary data |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Font's data |


---


### loadExternalFonts {#loadExternalFonts}

| Name | Description |
| --- | --- |
| loadExternalFonts (java.lang.String[]) | Adds additional folders to seek fonts. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Directories to read additional fonts. |


---


