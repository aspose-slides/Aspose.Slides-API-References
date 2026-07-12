---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /pt/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Retorno de chamada que será invocado para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) no [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Retorno de chamada que será invocado para cada \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) no [BaseSlide](../../com.aspose.slides/baseslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Porção iterada atual |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Parágrafo iterado atual |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide iterado atual |
| index | int | Índice do parágrafo atual no slide |