---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /th/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

อินเทอร์เฟซสำหรับคลาสที่รับคำเตือน
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | เมธอด callback ที่รับคำเตือนและตัดสินใจว่าจะยกเลิกการดำเนินการหรือไม่. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

เมธอด callback ที่รับคำเตือนและตัดสินใจว่าจะยกเลิกการดำเนินการหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | คำเตือนที่ต้องประมวลผล. |

**คืนค่า:**
int - การตัดสินใจยกเลิก [ReturnAction](../../com.aspose.slides/returnaction).