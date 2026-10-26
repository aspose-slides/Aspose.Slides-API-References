---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## 方法

| Method | Description |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | 回呼將於每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation) 中被呼叫。 |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

回呼將於每個 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation) 中被呼叫。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | 目前迭代的版面投影片 |
| index | int | 目前版面投影片的索引 |