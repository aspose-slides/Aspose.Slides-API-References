---
title: FontFallBackRule
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/fontfallbackrule/fontfallbackrule/
---

## FontFallBackRule(long startIndex, long endIndex, String fontNames)  constructor

 Creates new instance.
 

 
```php
  // Create new instance of FantFallBackRule with one font.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho");
  // Create new instance of FantFallBackRule with several fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | String | Font's name or names (delimited by comma) for FallBack |


---


## FontFallBackRule(long startIndex, long endIndex, java.lang.String[] fontNames)  constructor

 Creates new instance.
 

 
```php
  // Create new instance of FantFallBackRule with two fonts
  $newRule = new FontFallBackRule(0x3040, 0x309f, new String[]{ "MS Mincho", "MS Gothic" });
  // Create new instance of FantFallBackRule with several fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, new String[]{ "MS Gothic", "Tahoma, Times New Roman" });
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |


---


