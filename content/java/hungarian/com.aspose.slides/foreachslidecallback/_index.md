---
title: ForEach.ForEachSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachslidecallback/
---```
public static interface ForEach.ForEachSlideCallback
```
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Visszahívás, amely minden \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ben. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract void invoke(Slide slide, int index)
```


Visszahívás, amely minden \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Az aktuálisan iterált dia |
| index | int | Az aktuális dia indexe |