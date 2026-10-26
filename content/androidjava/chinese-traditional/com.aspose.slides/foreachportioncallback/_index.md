---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 此回呼將在 [BaseSlide](../../com.aspose.slides/baseslide) 上為每個 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 被呼叫。 |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

此回呼將在 [BaseSlide](../../com.aspose.slides/baseslide) 上為每個 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 被呼叫。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | 目前遍歷的部分 |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 目前遍歷的段落 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 目前遍歷的投影片 |
| index | int | 投影片上目前段落的索引 |