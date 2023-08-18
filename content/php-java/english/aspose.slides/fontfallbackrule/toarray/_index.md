---
title: toArray
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/fontfallbackrule/toarray/
---

## toArray()  method

 Creates and returns an array with all FallBack fonts for this rule.
 

### Returns
String


---


## toArray(int startIndex, int count)  method

 Creates and returns an array with all FallBack fonts from the specified range in list.
 
 // Create a rule contains a list of fonts.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Get a last two font names as array.
 String[] fontNames = newRule.toArray(2, 2);
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

### Returns
String


---


