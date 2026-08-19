---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /it/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metodi

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback che verrà invocato per ogni \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sul [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback che verrà invocato per ogni \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) sul [BaseSlide](../../com.aspose.slides/baseslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Porzione iterata corrente |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Paragrafo iterato corrente |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide iterata corrente |
| index | int | Indice del paragrafo corrente sulla slide |