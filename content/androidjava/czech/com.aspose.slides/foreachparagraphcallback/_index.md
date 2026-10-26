---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /cs/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback, který bude vyvolán pro každý \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

Callback, který bude vyvolán pro každý \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktuální iterovaný odstavec |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuální iterovaný snímek |
| index | int | Index aktuálního odstavce na snímku |