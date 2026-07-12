---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /es/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | callback que será invocado para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) en el [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


callback que será invocado para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) en el [BaseSlide](../../com.aspose.slides/baseslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Porción iterada actual |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Párrafo iterado actual |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositiva iterada actual |
| index | int | Índice del párrafo actual en la diapositiva |