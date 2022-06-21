---
title: toArray
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 150
url: /php-java/fontfallbackrule/toarray/
---

## toArray() method

 Creates and returns an array with all FallBack fonts for this rule.
 

 
```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Get all font names as array.
  $fontNames = $newRule->toArray();
```

### Returns
Array of String


---


## toArray(int, int) method

 Creates and returns an array with all FallBack fonts from the specified range in list.
 
 // Create a rule contains a list of fonts.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Get a last two font names as array.
 String[] fontNames = newRule.toArray(2, 2);
 
 

```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Get a last two font names as array.
  $fontNames = $newRule->toArray(2, 2);
```

### Parameters

| Name | Description |
| --- | --- |
| startIndex | An index of a first font to add. |
| count | A number of fonts to add. |

### Returns
Array of String


---


