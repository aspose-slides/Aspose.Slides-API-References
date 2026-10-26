---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /sv/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Återanrop som kommer att anropas för varje \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) på [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Återanrop som kommer att anropas för varje \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) på [BaseSlide](../../com.aspose.slides/baseslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Aktuell itererad del |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktuell itererad stycke |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuell itererad bild |
| index | int | Index för det aktuella stycket på bilden |