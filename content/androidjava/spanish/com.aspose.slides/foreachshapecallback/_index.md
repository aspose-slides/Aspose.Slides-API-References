---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /es/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback que será invocado para cada [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Callback que será invocado para cada [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Forma iterada actual |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositiva iterada actual |
| index | int | Índice de la diapositiva de diseño actual |