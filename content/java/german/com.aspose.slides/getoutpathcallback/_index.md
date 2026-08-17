---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /de/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Der Callback wird für jedes [Slide](../../com.aspose.slides/slide) aufgerufen, wobei der Ausgabepfad zurückgegeben werden soll. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Der Callback wird für jedes [Slide](../../com.aspose.slides/slide) aufgerufen, wobei der Ausgabepfad zurückgegeben werden soll.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Aktuell iterierte Folie |
| index | int | Index der aktuellen Folie |

**Rückgabewert:**
java.lang.String