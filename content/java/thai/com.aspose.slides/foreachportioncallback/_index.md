---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## เมธอด

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | คอลแบ็กที่จะถูกเรียกใช้สำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

คอลแบ็กที่จะถูกเรียกใช้สำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | ส่วนที่กำลังวนอยู่ในปัจจุบัน |
| para | [Paragraph](../../com.aspose.slides/paragraph) | ย่อหน้าที่กำลังวนอยู่ในปัจจุบัน |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์ที่กำลังวนอยู่ในปัจจุบัน |
| index | int | ดัชนีของย่อหน้าปัจจุบันบนสไลด์ |