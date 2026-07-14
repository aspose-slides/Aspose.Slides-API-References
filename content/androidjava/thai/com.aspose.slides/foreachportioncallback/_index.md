---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) บน [BaseSlide](../../com.aspose.slides/baseslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | ส่วนที่ทำการวนซ้ำในปัจจุบัน |
| para | [Paragraph](../../com.aspose.slides/paragraph) | ย่อหน้าที่ทำการวนซ้ำในปัจจุบัน |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์ที่ทำการวนซ้ำในปัจจุบัน |
| index | int | ดัชนีของย่อหน้าปัจจุบันบนสไลด์ |