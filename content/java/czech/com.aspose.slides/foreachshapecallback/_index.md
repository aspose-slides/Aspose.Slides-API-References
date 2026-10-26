---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /cs/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Zpětné volání, které bude vyvoláno pro každý [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Zpětné volání, které bude vyvoláno pro každý [Shape](../../com.aspose.slides/shape) v [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Aktuální iterovaný tvar |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuální iterovaný snímek |
| index | int | Index aktuálního rozložení snímku |