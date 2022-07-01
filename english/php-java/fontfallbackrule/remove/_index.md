---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/fontfallbackrule/remove/
---

## remove(String fontName)  method

 Removes the first occurrence of a specific FallBack font from the list.
 

 
```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Remove Tahoma from the list.
  $newRule->remove("Tahoma");
```

### Parameters

| Name | Description |
| --- | --- |
| fontName | The font's name to remove from the list. |


---


