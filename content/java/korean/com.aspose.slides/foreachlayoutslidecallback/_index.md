---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | 각 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 에 대해 호출되는 콜백이며, [Presentation](../../com.aspose.slides/presentation)에 있습니다. |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```


각 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 에 대해 호출되는 콜백이며, [Presentation](../../com.aspose.slides/presentation)에 있습니다.

**매개 변수:**
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | 현재 반복 중인 레이아웃 슬라이드 |
| index | int | 현재 레이아웃 슬라이드의 인덱스 |