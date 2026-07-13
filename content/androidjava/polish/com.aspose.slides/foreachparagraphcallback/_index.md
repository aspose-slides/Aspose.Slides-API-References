---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /pl/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Wywołanie zwrotne, które zostanie wywołane dla każdego \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

Wywołanie zwrotne, które zostanie wywołane dla każdego \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Bieżący iterowany akapit |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Bieżący iterowany slajd |
| index | int | Indeks bieżącego akapitu na slajdzie |