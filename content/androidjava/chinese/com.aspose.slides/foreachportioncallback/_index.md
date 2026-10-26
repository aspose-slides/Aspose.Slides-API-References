---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /zh/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 在每个 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 上的 [BaseSlide](../../com.aspose.slides/baseslide) 被调用的回调。 |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

在每个 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 上的 [BaseSlide](../../com.aspose.slides/baseslide) 被调用的回调。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | 当前迭代的部分 |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 当前迭代的段落 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 当前迭代的幻灯片 |
| index | int | 幻灯片上当前段落的索引 |