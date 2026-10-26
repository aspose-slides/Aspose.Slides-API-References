---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: 
type: docs
url: /th/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [Slide](../../com.aspose.slides/slide) และคาดว่าจะคืนเส้นทางออก |

### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [Slide](../../com.aspose.slides/slide) และคาดว่าจะคืนเส้นทางออก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | สไลด์ที่กำลังถูกวนปัจจุบัน |
| index | int | ดัชนีของสไลด์ปัจจุบัน |

**คืนค่า:**
java.lang.String