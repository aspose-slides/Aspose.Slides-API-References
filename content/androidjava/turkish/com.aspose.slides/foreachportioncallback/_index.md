---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /tr/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Her \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) için [BaseSlide](../../com.aspose.slides/baseslide) üzerinde tetiklenecek geri arama. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Her \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) için [BaseSlide](../../com.aspose.slides/baseslide) üzerinde tetiklenecek geri arama.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Mevcut yineleme yapılan bölüm |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Mevcut yineleme yapılan paragraf |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Mevcut yineleme yapılan slayt |
| index | int | Slayttaki mevcut paragrafın indeksi |