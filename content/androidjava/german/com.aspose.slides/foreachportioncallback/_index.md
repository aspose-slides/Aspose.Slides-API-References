---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /de/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Methoden

| Method | Beschreibung |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Rückruf, der für jedes \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) auf dem [BaseSlide](../../com.aspose.slides/baseslide) aufgerufen wird. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Rückruf, der für jedes \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) auf dem [BaseSlide](../../com.aspose.slides/baseslide) aufgerufen wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Aktuell iterierter Teil |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktuell iterierter Absatz |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuell iterierte Folie |
| index | int | Index des aktuellen Absatzes auf der Folie |