---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /nl/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback die wordt aangeroepen voor elke [Shape](../../com.aspose.slides/shape) in de [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Callback die wordt aangeroepen voor elke [Shape](../../com.aspose.slides/shape) in de [Presentation](../../com.aspose.slides/presentation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Huidige doorlopen vorm |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Huidige doorlopen dia |
| index | int | Index van de huidige layout-dial |