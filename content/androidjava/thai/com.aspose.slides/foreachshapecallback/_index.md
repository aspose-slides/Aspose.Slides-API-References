---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | คอลแบ็คที่จะถูกเรียกสำหรับแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

คอลแบ็คที่จะถูกเรียกสำหรับแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | รูปที่กำลังวนซ้ำปัจจุบัน |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์ที่กำลังวนซ้ำปัจจุบัน |
| index | int | ดัชนีของสไลด์เค้าโครงปัจจุบัน |