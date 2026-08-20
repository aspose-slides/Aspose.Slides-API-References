---
title: ForEach.ForEachMasterSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachmasterslidecallback/
---```
public static interface ForEach.ForEachMasterSlideCallback
```
## 方法

| Method | 說明 |
| --- | --- |
| [invoke(MasterSlide masterSlide, int index)](#invoke-com.aspose.slides.MasterSlide-int-) | 此回呼會在 [Presentation](../../com.aspose.slides/presentation) 中針對每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 被呼叫。 |
### invoke(MasterSlide masterSlide, int index) {#invoke-com.aspose.slides.MasterSlide-int-}
```
public abstract void invoke(MasterSlide masterSlide, int index)
```


此回呼會在 [Presentation](../../com.aspose.slides/presentation) 中針對每個 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 被呼叫。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| masterSlide | [MasterSlide](../../com.aspose.slides/masterslide) | 目前遍歷的母片投影片 |
| index | int | 目前母片投影片的索引 |