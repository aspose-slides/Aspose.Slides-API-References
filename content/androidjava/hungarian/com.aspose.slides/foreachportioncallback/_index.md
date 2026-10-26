---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /hu/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Módszerek

| Method | Leírás |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Visszahívás, amely minden \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén meghívásra kerül a [BaseSlide](../../com.aspose.slides/baseslide)-on. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Visszahívás, amely minden \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) esetén meghívásra kerül a [BaseSlide](../../com.aspose.slides/baseslide)-on.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | A jelenleg iterált rész |
| para | [Paragraph](../../com.aspose.slides/paragraph) | A jelenleg iterált bekezdés |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | A jelenleg iterált dia |
| index | int | A jelenlegi bekezdés indexe a dián |