---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /cs/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback, který bude vyvolán pro každý [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Callback, který bude vyvolán pro každý [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Aktuální iterovaný shape |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuální iterovaný slide |
| index | int | Index aktuálního rozvrhového slide |