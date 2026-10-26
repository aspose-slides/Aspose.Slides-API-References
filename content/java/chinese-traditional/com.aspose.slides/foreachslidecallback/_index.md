---
title: ForEach.ForEachSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachslidecallback/
---```
public static interface ForEach.ForEachSlideCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 回呼將在每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 中於 [Presentation](../../com.aspose.slides/presentation) 被觸發。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract void invoke(Slide slide, int index)
```

回呼將在每個 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 中於 [Presentation](../../com.aspose.slides/presentation) 被觸發。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 目前迭代的投影片 |
| index | int | 目前投影片的索引 |