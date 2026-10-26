---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: 
type: docs
url: /ar/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | ستتم استدعاء Callback لكل \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) على [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

ستتم استدعاء Callback لكل \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) على [BaseSlide](../../com.aspose.slides/baseslide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | الفقرة الحالية المتكررة |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | الشريحة الحالية المتكررة |
| index | int | فهرس الفقرة الحالية في الشريحة |