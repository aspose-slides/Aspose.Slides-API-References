---
title: indexOf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 190
url: /php-java/fontfallbackrule/indexof/
---

## indexOf(String fontName)  method

 Returns an index of the specified rule in the collection.
 

 
```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Get index of Tahoma.
  $tahomaIndex = $newRule->indexOf("Tahoma");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontName | String | Font's name to find. |

### Returns
int


---


