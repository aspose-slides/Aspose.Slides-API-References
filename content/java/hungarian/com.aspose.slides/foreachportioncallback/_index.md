---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | A visszahívás, amely minden \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén a [BaseSlide](../../com.aspose.slides/baseslide)-on kerül meghívásra. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


A visszahívás, amely minden \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén a [BaseSlide](../../com.aspose.slides/baseslide)-on kerül meghívásra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Jelenlegi iterált rész |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Jelenlegi iterált bekezdés |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Jelenlegi iterált dia |
| index | int | A jelenlegi bekezdés a diáron lévő indexe |