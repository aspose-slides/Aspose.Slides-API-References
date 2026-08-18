---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /pl/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Wywołanie zwrotne, które zostanie wywołane dla każdego \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Wywołanie zwrotne, które zostanie wywołane dla każdego \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) na [BaseSlide](../../com.aspose.slides/baseslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Aktualny iterowany fragment |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Aktualny iterowany akapit |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Aktualny iterowany slajd |
| index | int | Indeks aktualnego akapitu na slajdzie |