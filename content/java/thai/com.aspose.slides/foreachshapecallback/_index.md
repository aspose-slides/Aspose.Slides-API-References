---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | รูปร่างที่ทำการวนในปัจจุบัน |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์ที่ทำการวนในปัจจุบัน |
| index | int | ดัชนีของสไลด์เลย์เอาต์ปัจจุบัน |