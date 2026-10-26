---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback ที่จะถูกเรียกสำหรับแต่ละ [Slide](../../com.aspose.slides/slide), เส้นทางผลลัพธ์ที่คาดว่าจะถูกส่งคืน. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Callback ที่จะถูกเรียกสำหรับแต่ละ [Slide](../../com.aspose.slides/slide), เส้นทางผลลัพธ์ที่คาดว่าจะถูกส่งคืน.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | สไลด์ที่กำลังวนลูปอยู่ |
| index | int | ดัชนีของสไลด์ปัจจุบัน |

**Returns:**
java.lang.String