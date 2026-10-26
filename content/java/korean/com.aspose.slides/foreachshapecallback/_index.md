---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | [Presentation](../../com.aspose.slides/presentation)의 각 [Shape](../../com.aspose.slides/shape)에 대해 호출되는 콜백입니다. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


[Presentation](../../com.aspose.slides/presentation)의 각 [Shape](../../com.aspose.slides/shape)에 대해 호출되는 콜백입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 현재 반복되는 도형 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 현재 반복되는 슬라이드 |
| index | int | 현재 레이아웃 슬라이드의 인덱스 |