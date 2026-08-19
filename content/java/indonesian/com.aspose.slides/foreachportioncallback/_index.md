---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /id/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback yang akan dipanggil untuk setiap \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) pada [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback yang akan dipanggil untuk setiap \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) pada [BaseSlide](../../com.aspose.slides/baseslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Bagian yang sedang diiterasi |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Paragraf yang sedang diiterasi |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide yang sedang diiterasi |
| index | int | Indeks paragraf saat ini pada slide |