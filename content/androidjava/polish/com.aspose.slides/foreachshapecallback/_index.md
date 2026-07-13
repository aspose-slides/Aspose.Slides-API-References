---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /pl/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Wywołanie zwrotne, które zostanie wywołane dla każdego [Shape](../../com.aspose.slides/shape) w [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Wywołanie zwrotne, które zostanie wywołane dla każdego [Shape](../../com.aspose.slides/shape) w [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Bieżący iterowany kształt |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Bieżący iterowany slajd |
| index | int | Indeks bieżącego slajdu układu |