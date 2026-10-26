---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /fa/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | کال‌بک که برای هر #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) فراخوانی می‌شود بر روی [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

کال‌بک که برای هر #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) فراخوانی می‌شود بر روی [BaseSlide](../../com.aspose.slides/baseslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | بخش جاری تکراری |
| para | [Paragraph](../../com.aspose.slides/paragraph) | پاراگراف جاری تکراری |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | اسلاید جاری تکراری |
| index | int | اندیس پاراگراف جاری در اسلاید |