---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /vi/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback sẽ được gọi cho mỗi \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) trên [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


Callback sẽ được gọi cho mỗi \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) trên [BaseSlide](../../com.aspose.slides/baseslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Đoạn hiện tại được lặp |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide hiện tại được lặp |
| index | int | Chỉ mục của đoạn hiện tại trên slide |