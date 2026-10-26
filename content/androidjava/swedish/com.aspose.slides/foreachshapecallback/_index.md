---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /sv/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Återanrop som kommer att anropas för varje [Shape](../../com.aspose.slides/shape) i [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Återanrop som kommer att anropas för varje [Shape](../../com.aspose.slides/shape) i [Presentation](../../com.aspose.slides/presentation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Aktuell itererad shape |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuell itererad slide |
| index | int | Index för den aktuella layout slide |