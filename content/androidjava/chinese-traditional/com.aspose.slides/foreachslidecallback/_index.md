---
title: ForEach.ForEachSlideCallback
second_title: Aspose.Slides 適用於 Android 的 Java API 參考
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachslidecallback/
---```
public static interface ForEach.ForEachSlideCallback
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 回呼，將於每個 #slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation) 中被呼叫。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract void invoke(Slide slide, int index)
```

回呼，將於每個 #slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) 在 [Presentation](../../com.aspose.slides/presentation) 中被呼叫。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 當前迭代的投影片 |
| index | int | 當前投影片的索引 |