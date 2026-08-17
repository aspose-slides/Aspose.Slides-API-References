---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | 此回调将在每个 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 被调用，位于 [Presentation](../../com.aspose.slides/presentation)。 |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

此回调将在每个 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 被调用，位于 [Presentation](../../com.aspose.slides/presentation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | 当前迭代的布局幻灯片 |
| index | int | 当前布局幻灯片的索引 |