---
title: indexOf
type: docs
weight: 100
url: /php-java/fontfallbackrule/indexof/
---

# indexOf(java.lang.String) method

 Returns an index of the specified rule in the collection.
 

 
```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Get index of Tahoma.
  $tahomaIndex = $newRule->indexOf("Tahoma");
```

##  Parameters

| name | description |
| --- | --- |
| fontName | Font's name to find. |

##  Returns
Index of a font or -1 if font not found in list.


