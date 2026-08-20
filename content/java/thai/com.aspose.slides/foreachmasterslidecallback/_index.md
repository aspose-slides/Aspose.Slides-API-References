---
title: ForEach.ForEachMasterSlideCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachmasterslidecallback/
---```
public static interface ForEach.ForEachMasterSlideCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(MasterSlide masterSlide, int index)](#invoke-com.aspose.slides.MasterSlide-int-) | คอลแบ็กที่จะถูกเรียกใช้สำหรับแต่ละ \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation). |
### invoke(MasterSlide masterSlide, int index) {#invoke-com.aspose.slides.MasterSlide-int-}
```
public abstract void invoke(MasterSlide masterSlide, int index)
```


คอลแบ็กที่จะถูกเรียกใช้สำหรับแต่ละ \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| masterSlide | [MasterSlide](../../com.aspose.slides/masterslide) | สไลด์หลักที่กำลังวนซ้ำอยู่ในปัจจุบัน |
| index | int | ดัชนีของสไลด์หลักในปัจจุบัน |