---
title: InterruptionToken
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คลาสนี้เป็นตัวแทนของโทเค็นที่ใช้สำหรับบ่งชี้งานที่ทำงานเป็นเวลานานว่ามีการขอการหยุดหรือไม่
type: docs
url: /th/com.aspose.slides/interruptiontoken/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

คลาสนี้เป็นตัวแทนของโทเค็นที่ใช้สำหรับบ่งชี้งานที่ทำงานเป็นเวลานานว่าได้มีการขอการหยุดหรือไม่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getNone()](#getNone--) | แสดงถึงโทเค็นการหยุดที่ว่างเปล่า |
| [isInterruptionRequested()](#isInterruptionRequested--) | คืนค่า true หากมีการขอการหยุด |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | โยนข้อยกเว้นหากมีการขอการหยุด |

### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

แสดงถึงโทเค็นการหยุดที่ว่างเปล่า

--------------------

การดำเนินการที่ใช้เวลานานจะไม่ถูกขัดจังหวะผ่าน [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) เมื่อใช้โทเค็นนี้

**ผลลัพธ์:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

คืนค่า true หากมีการขอการหยุด

**ผลลัพธ์:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

โยนข้อยกเว้นหากมีการขอการหยุด.