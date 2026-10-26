---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /fa/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback که برای هر \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) بر روی [BaseSlide](../../com.aspose.slides/baseslide) فراخوانی خواهد شد. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback که برای هر \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) بر روی [BaseSlide](../../com.aspose.slides/baseslide) فراخوانی خواهد شد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | بخش فعلی در حال تکرار |
| para | [Paragraph](../../com.aspose.slides/paragraph) | پاراگراف فعلی در حال تکرار |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | اسلاید فعلی در حال تکرار |
| index | int | اندیس پاراگراف فعلی در اسلاید |