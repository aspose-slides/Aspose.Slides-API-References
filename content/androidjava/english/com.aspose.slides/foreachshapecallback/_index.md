---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
weight: 14
url: /com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback that will be invoked for each [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Callback that will be invoked for each [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Current iterated shape |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Current iterated slide |
| index | int | Index of the current layout slide |

