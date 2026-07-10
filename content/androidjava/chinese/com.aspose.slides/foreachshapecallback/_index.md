---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /zh/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | 将在 [Presentation](../../com.aspose.slides/presentation) 中为每个 [Shape](../../com.aspose.slides/shape) 调用的回调。 |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

将在 [Presentation](../../com.aspose.slides/presentation) 中为每个 [Shape](../../com.aspose.slides/shape) 调用的回调。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 当前迭代的形状 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 当前迭代的幻灯片 |
| index | int | 当前布局幻灯片的索引 |