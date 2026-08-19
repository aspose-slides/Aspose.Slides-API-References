---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /it/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback che verrà invocato per ogni [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Callback che verrà invocato per ogni [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | shape attualmente iterata |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | slide attualmente iterata |
| index | int | Indice della slide di layout corrente |