---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /cs/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Zpětné volání, které bude vyvoláno pro každý [Slide](../../com.aspose.slides/slide), očekává se, že bude vrácena výstupní cesta. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Zpětné volání, které bude vyvoláno pro každý [Slide](../../com.aspose.slides/slide), očekává se, že bude vrácena výstupní cesta.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Aktuální iterovaný snímek |
| index | int | Index aktuálního snímku |

**Návratová hodnota:**
java.lang.String