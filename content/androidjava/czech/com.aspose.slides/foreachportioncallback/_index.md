---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /cs/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metody

| Metoda | Popis |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Zpětné volání, které bude vyvoláno pro každý \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Zpětné volání, které bude vyvoláno pro každý \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Aktuální iterovaná část |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktuální iterovaný odstavec |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktuální iterovaný snímek |
| index | int | Index aktuálního odstavce na snímku |