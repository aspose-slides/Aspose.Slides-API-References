---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /es/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback que se invocará para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) en el [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

Callback que se invocará para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) en el [BaseSlide](../../com.aspose.slides/baseslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Párrafo iterado actual |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositiva iterada actual |
| index | int | Índice del párrafo actual en la diapositiva |