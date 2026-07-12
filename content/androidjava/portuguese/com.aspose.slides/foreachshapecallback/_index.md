---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /pt/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback que será invocado para cada [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Callback que será invocado para cada [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Forma iterada atual |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide iterado atual |
| index | int | Índice do slide de layout atual |