---
title: FontFallBackRule
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/fontfallbackrule/fontfallbackrule/
---

## FontFallBackRule(long, long, java.lang.String) constructor

Creates new instance.

 
```php
  // Create new instance of FantFallBackRule with one font.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho");
  // Create new instance of FantFallBackRule with several fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma");
```

### Parameters

| Parameter |Description |
| --- | --- |
| startIndex | Start index of unicode range |
| endIndex | End index of unicode range |
| fontNames | Font's name or names (delimited by comma) for FallBack |
 

---


## FontFallBackRule(long, long, java.lang.String[]) constructor

Creates new instance.

 
```php
  // Create new instance of FantFallBackRule with two fonts
  $newRule = new FontFallBackRule(0x3040, 0x309f, new String[]{ "MS Mincho", "MS Gothic" });
  // Create new instance of FantFallBackRule with several fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, new String[]{ "MS Gothic", "Tahoma, Times New Roman" });
```

### Parameters

| Parameter |Description |
| --- | --- |
| startIndex | Start index of unicode range |
| endIndex | End index of unicode range |
| fontNames | Font's name or names (delimited by comma) for FallBack |
 

---


