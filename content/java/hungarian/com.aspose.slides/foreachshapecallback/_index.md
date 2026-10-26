---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Visszahívás, amely minden [Shape](../../com.aspose.slides/shape) esetén a [Presentation](../../com.aspose.slides/presentation)-ban lesz meghívva. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Visszahívás, amely minden [Shape](../../com.aspose.slides/shape) esetén a [Presentation](../../com.aspose.slides/presentation)-ban lesz meghívva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Az aktuálisan bejárandó alakzat |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Az aktuálisan bejárandó dia |
| index | int | Az aktuális elrendezési dia indexe |