---
title: Fonts
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/fonts/
---

## Fonts class

 Fonts collection.
 
### getComplexScriptFont {#getComplexScriptFont}

| Name | Description |
| --- | --- |
| getComplexScriptFont() | Returns or sets the complex script font. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getEastAsianFont {#getEastAsianFont}

| Name | Description |
| --- | --- |
| getEastAsianFont() | Returns or sets the East Asian font. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getLatinFont {#getLatinFont}

| Name | Description |
| --- | --- |
| getLatinFont() | Returns or sets the Latin font. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getScriptFont {#getScriptFont}

| Name | Description |
| --- | --- |
| getScriptFont(String) | Gets the font name associated with a specific script tag from the presentation theme. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| script | String | The BCP-47 script code (e.g., "Latn", "Cyrl", "Jpan") used to identify a writing system. |

 **Returns:**
String


---


### getScriptFontMap {#getScriptFontMap}

| Name | Description |
| --- | --- |
| getScriptFontMap() | Returns a dictionary of all script font definitions in the presentation. |

 **Returns:**
Dictionary


---


### removeScriptFont {#removeScriptFont}

| Name | Description |
| --- | --- |
| removeScriptFont(String) | Removes the font setting associated with a specific script tag from the theme's font collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| script | String | The BCP-47 script code whose font setting should be removed. |


---


### setComplexScriptFont {#setComplexScriptFont}

| Name | Description |
| --- | --- |
| setComplexScriptFont([FontData](../fontdata)) | Returns or sets the complex script font. Read/write IFontData. |


---


### setEastAsianFont {#setEastAsianFont}

| Name | Description |
| --- | --- |
| setEastAsianFont([FontData](../fontdata)) | Returns or sets the East Asian font. Read/write IFontData. |


---


### setLatinFont {#setLatinFont}

| Name | Description |
| --- | --- |
| setLatinFont([FontData](../fontdata)) | Returns or sets the Latin font. Read/write IFontData. |


---


### setScriptFont {#setScriptFont}

| Name | Description |
| --- | --- |
| setScriptFont(String, String) | Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| script | String | The BCP-47 script code (e.g., "Arab", "Hebr", "Hans") identifying the writing system. |
| fontName | String | The name of the font to assign to the specified script. |


---


