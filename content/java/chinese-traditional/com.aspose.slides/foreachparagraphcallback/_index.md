---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 回呼將在 [BaseSlide](../../com.aspose.slides/baseslide) 上針對每個 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 被呼叫。 |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


回呼將在 [BaseSlide](../../com.aspose.slides/baseslide) 上針對每個 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 被呼叫。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 目前迭代的段落 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 目前迭代的投影片 |
| index | int | 目前段落在投影片上的索引 |