---
title: InterruptionToken
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสนี้เป็นตัวแทนของโทเค็นที่ใช้สำหรับสัญญาณงานที่ทำงานระยะยาวว่ามีการร้องขอการขัดจังหวะหรือไม่.
type: docs
url: /th/com.aspose.slides/interruptiontoken/
---
**การสืบทอด:**  
java.lang.Object  

**อินเทอร์เฟซที่ทำตามทั้งหมด:**  
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)  
```
public class InterruptionToken implements IInterruptionToken
```

คลาสนี้เป็นตัวแทนของโทเค็นที่ใช้ในการสัญญาณงานที่ทำงานระยะยาวว่ามีการร้องขอการขัดจังหวะหรือไม่.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getNone()](#getNone--) | เป็นตัวแทนของโทเค็นการขัดจังหวะที่ว่างเปล่า. |
| [isInterruptionRequested()](#isInterruptionRequested--) | คืนค่า true หากมีการร้องขอการขัดจังหวะ. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | โยนข้อยกเว้นหากมีการร้องขอการขัดจังหวะ. |

### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

เป็นตัวแทนของโทเค็นการขัดจังหวะที่ว่างเปล่า.

--------------------

การทำงานระยะยาวจะไม่ถูกขัดจังหวะผ่าน [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) เมื่อใช้โทเค็นนี้.

**คืนค่า:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

คืนค่า true หากมีการร้องขอการขัดจังหวะ.

**คืนค่า:**  
boolean

### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

โยนข้อยกเว้นหากมีการร้องขอการขัดจังหวะ.