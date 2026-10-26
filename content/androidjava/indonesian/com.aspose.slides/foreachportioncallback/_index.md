---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /id/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Metode

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback yang akan dipanggil untuk setiap #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) pada [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Callback yang akan dipanggil untuk setiap #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) pada [BaseSlide](../../com.aspose.slides/baseslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | portion yang sedang diiterasi |
| para | [Paragraph](../../com.aspose.slides/paragraph) | paragraph yang sedang diiterasi |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | slide yang sedang diiterasi |
| index | int | Indeks dari paragraph saat ini pada slide |