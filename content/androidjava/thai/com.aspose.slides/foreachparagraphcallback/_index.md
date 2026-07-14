---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | คอลแบ็กที่ถูกเรียกใช้สำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


คอลแบ็กที่ถูกเรียกใช้สำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | ย่อหน้าที่กำลังวนซ้ำปัจจุบัน |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์ที่กำลังวนซ้ำปัจจุบัน |
| index | int | ดัชนีของย่อหน้าปัจจุบันบนสไลด์ |