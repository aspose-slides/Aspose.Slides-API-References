---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ar/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | استدعاء سيُنفذ لكل \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) على الـ [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

استدعاء سيُنفذ لكل \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) على الـ [BaseSlide](../../com.aspose.slides/baseslide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | الجزء الحالي المتكرر |
| para | [Paragraph](../../com.aspose.slides/paragraph) | الفقرة الحالية المتكررة |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | الشريحة الحالية المتكررة |
| index | int | فهرس الفقرة الحالية على الشريحة |