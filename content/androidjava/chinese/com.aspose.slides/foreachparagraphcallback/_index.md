---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 
type: docs
url: /zh/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 在每个 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 上调用的回调，针对 [BaseSlide](../../com.aspose.slides/baseslide)。 |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

将在每个 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 上调用的回调，针对 [BaseSlide](../../com.aspose.slides/baseslide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 当前迭代的段落 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 当前迭代的幻灯片 |
| index | int | 幻灯片上当前段落的索引 |