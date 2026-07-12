---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /de/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Methoden

| Method | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback, der für jedes [Shape](../../com.aspose.slides/shape) im [Presentation](../../com.aspose.slides/presentation) aufgerufen wird. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Callback, der für jedes [Shape](../../com.aspose.slides/shape) im [Presentation](../../com.aspose.slides/presentation) aufgerufen wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Aktuell iterierte Form |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuell iterierte Folie |
| index | int | Index der aktuellen Layout-Folie |