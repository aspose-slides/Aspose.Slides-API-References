---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Módszerek

| Method | Leírás |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Visszahívás, amely minden #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén meghívásra kerül a [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


Visszahívás, amely minden #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén meghívásra kerül a [BaseSlide](../../com.aspose.slides/baseslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktuálisan iterált bekezdés |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuálisan iterált diák |
| index | int | A dián lévő aktuális bekezdés indexe |