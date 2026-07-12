---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Visszahívás, amely minden [Shape](../../com.aspose.slides/shape) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ban. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Visszahívás, amely minden [Shape](../../com.aspose.slides/shape) esetén meghívásra kerül a [Presentation](../../com.aspose.slides/presentation)-ban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Aktuális iterált alakzat |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuális iterált dia |
| index | int | Az aktuális elrendezési dia indexe |