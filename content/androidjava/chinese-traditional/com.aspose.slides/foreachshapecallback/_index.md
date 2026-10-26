---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | 將在 [Presentation](../../com.aspose.slides/presentation) 中為每個 [Shape](../../com.aspose.slides/shape) 呼叫的回呼。 |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


將在 [Presentation](../../com.aspose.slides/presentation) 中為每個 [Shape](../../com.aspose.slides/shape) 呼叫的回呼。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 目前迭代的圖形 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 目前迭代的投影片 |
| index | int | 目前版面投影片的索引 |