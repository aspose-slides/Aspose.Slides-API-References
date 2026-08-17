---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /tr/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Her \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) için tetiklenecek geri çağırma [BaseSlide](../../com.aspose.slides/baseslide) üzerinde. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Her \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) için tetiklenecek geri çağırma [BaseSlide](../../com.aspose.slides/baseslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Geçerli yineleme bölümü |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Geçerli yineleme paragrafı |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Geçerli yineleme slaytı |
| index | int | Slayttaki geçerli paragrafın indeksi |