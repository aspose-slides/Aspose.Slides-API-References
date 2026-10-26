---
title: ForEach.ForEachSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachslidecallback/
---```
public static interface ForEach.ForEachSlideCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback that will be invoked for each #slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) in the [Presentation](../../com.aspose.slides/presentation). |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract void invoke(Slide slide, int index)
```

Callback that will be invoked for each #slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) in the [Presentation](../../com.aspose.slides/presentation).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 현재 반복 중인 슬라이드 |
| index | int | 현재 슬라이드의 인덱스 |