---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: ส่วนต่อประสานสำหรับคลาสที่รับการเตือน
type: docs
url: /th/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

ส่วนต่อประสานสำหรับคลาสที่รับการเตือน
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | วิธีเรียกกลับที่รับการเตือนและตัดสินใจว่าควรยกเลิกการทำงานหรือไม่ |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

วิธีเรียกกลับที่รับการเตือนและตัดสินใจว่าควรยกเลิกการทำงานหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | คำเตือนที่ต้องประมวลผล |

**ผลลัพธ์:**
int - การตัดสินใจยกเลิก [ReturnAction](../../com.aspose.slides/returnaction).