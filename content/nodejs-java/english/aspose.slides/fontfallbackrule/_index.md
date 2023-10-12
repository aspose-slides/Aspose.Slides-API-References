---
title: FontFallBackRule
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/fontfallbackrule/
---

## FontFallBackRule class

 Represents font fallback rule
 
| [FontFallBackRule]([long], [long], [String]) | Creates new instance. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | [long] | Start index of unicode range |
| endIndex | [long] | End index of unicode range |
| fontNames | [String] | Font's name or names (delimited by comma) for FallBack |

### Result
FontFallBackRule


---


| [FontFallBackRule]([long], [long], [java.lang.String[]]) | Creates new instance. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | [long] | Start index of unicode range |
| endIndex | [long] | End index of unicode range |
| fontNames | [java.lang.String[]] | Font's name or names (delimited by comma) for FallBack |

### Result
FontFallBackRule


---


| [addFallBackFonts] ([String]) | Adds a new font(s) to the list of FallBack fonts. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontName | [String] | Font's name or names (delimited by comma) for FallBack |


---


| [addFallBackFonts] ([java.lang.String[]]) | Adds a new fonts to the list of FallBack fonts. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontNames | [java.lang.String[]] | Font's name or names (delimited by comma) for FallBack |


---


| [clear] () | Removes all fonts from the list. |


---


| [getCount] () | Gets the number of fonts actually defined for range. Read-only int. |

### Result
int


---


| [getRangeEndIndex] () | Get last index of continuous unicode range. |

### Result
long


---


| [getRangeStartIndex] () | Get first index of continuous unicode range. |

### Result
long


---


| [get_Item] ([int]) | Gets the font name at the specified index. Read-only IFontFallBackRule. |

### Result
String


---


| [indexOf] ([String]) | Returns an index of the specified rule in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontName | [String] | Font's name to find. |

### Result
int


---


| [remove] ([String]) | Removes the first occurrence of a specific FallBack font from the list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontName | [String] | The font's name to remove from the list. |


---


| [removeAt] ([int]) | Removes the FallBack font at the specified index of the list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the font to remove. |


---


| [setRangeEndIndex] ([long]) | Get last index of continuous unicode range. |


---


| [setRangeStartIndex] ([long]) | Get first index of continuous unicode range. |


---


| [toArray] () | Creates and returns an array with all FallBack fonts for this rule. |

### Result
String


---


| [toArray] ([int], [int]) | Creates and returns an array with all FallBack fonts from the specified range in list. // Create a rule contains a list of fonts. IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman"); // Get a last two font names as array. String[] fontNames = newRule.toArray(2, 2); |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | [int] | An index of a first font to add. |
| count | [int] | A number of fonts to add. |

### Result
String


---


