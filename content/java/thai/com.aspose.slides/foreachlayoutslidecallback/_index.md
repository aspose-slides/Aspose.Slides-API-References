---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation). |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

Callback ที่จะถูกเรียกใช้สำหรับแต่ละ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | สไลด์เค้าโครงที่กำลังวนลูปอยู่ปัจจุบัน |
| index | int | ดัชนีของสไลด์เค้าโครงปัจจุบัน |