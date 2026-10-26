---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | 각 [Shape](../../com.aspose.slides/shape)에 대해 [Presentation](../../com.aspose.slides/presentation)에서 호출되는 콜백입니다. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

각 [Shape](../../com.aspose.slides/shape)에 대해 [Presentation](../../com.aspose.slides/presentation)에서 호출되는 콜백입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 현재 반복되는 shape |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 현재 반복되는 slide |
| index | int | 현재 레이아웃 slide의 인덱스 |