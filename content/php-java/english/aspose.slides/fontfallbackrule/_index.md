---
title: FontFallBackRule
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/fontfallbackrule/
---

## FontFallBackRule class

 Represents font fallback rule
 
### FontFallBackRule {#FontFallBackRule}

| Name | Description |
| --- | --- |
| FontFallBackRule(long, long, String) | Creates new instance. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | String | Font's name or names (delimited by comma) for FallBack |

 **Returns:**
FontFallBackRule


---


### FontFallBackRule {#FontFallBackRule}

| Name | Description |
| --- | --- |
| FontFallBackRule(long, long, java.lang.String[]) | Creates new instance. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

 **Returns:**
FontFallBackRule


---


### addFallBackFonts {#addFallBackFonts}

| Name | Description |
| --- | --- |
| addFallBackFonts (String) | Adds a new font(s) to the list of FallBack fonts. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontName | String | Font's name or names (delimited by comma) for FallBack |

 **Returns:**
void


---


### addFallBackFonts {#addFallBackFonts}

| Name | Description |
| --- | --- |
| addFallBackFonts (java.lang.String[]) | Adds a new fonts to the list of FallBack fonts. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

 **Returns:**
void


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all fonts from the list. |

 **Returns:**
void


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Gets the number of fonts actually defined for range. Read-only int. |

 **Returns:**
int


---


### getRangeEndIndex {#getRangeEndIndex}

| Name | Description |
| --- | --- |
| getRangeEndIndex () | Get last index of continuous unicode range. |

 **Returns:**
long


---


### getRangeStartIndex {#getRangeStartIndex}

| Name | Description |
| --- | --- |
| getRangeStartIndex () | Get first index of continuous unicode range. |

 **Returns:**
long


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the font name at the specified index. Read-only IFontFallBackRule. |

 **Returns:**
String


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf (String) | Returns an index of the specified rule in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontName | String | Font's name to find. |

 **Returns:**
int


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove (String) | Removes the first occurrence of a specific FallBack font from the list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontName | String | The font's name to remove from the list. |

 **Returns:**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the FallBack font at the specified index of the list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

 **Returns:**
void


---


### setRangeEndIndex {#setRangeEndIndex}

| Name | Description |
| --- | --- |
| setRangeEndIndex (long) | Get last index of continuous unicode range. |

 **Returns:**
void


---


### setRangeStartIndex {#setRangeStartIndex}

| Name | Description |
| --- | --- |
| setRangeStartIndex (long) | Get first index of continuous unicode range. |

 **Returns:**
void


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array with all FallBack fonts for this rule. |

 **Returns:**
String


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Creates and returns an array with all FallBack fonts from the specified range in list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

 **Returns:**
String


---


