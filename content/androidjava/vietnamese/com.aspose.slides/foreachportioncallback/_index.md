---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /vi/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Phương thức

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback sẽ được gọi cho mỗi \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) trên [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


Callback sẽ được gọi cho mỗi \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) trên [BaseSlide](../../com.aspose.slides/baseslide).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Phần hiện tại đang được lặp |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Đoạn văn hiện tại đang được lặp |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide hiện tại đang được lặp |
| index | int | Chỉ mục của đoạn văn hiện tại trên slide |