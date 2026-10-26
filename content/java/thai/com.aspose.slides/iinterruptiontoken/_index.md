---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /th/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

คลาสนี้แสดงถึงโทเคนที่ใช้สำหรับสัญญาณงานที่ใช้เวลานานว่าการขัดจังหวะได้ถูกร้องขอหรือไม่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | คืนค่า true หากมีการขัดจังหวะที่ร้องขอ. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | โยนข้อยกเว้นหากมีการขัดจังหวะที่ร้องขอ. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


คืนค่า true หากมีการขัดจังหวะที่ร้องขอ.

**คืนค่า:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


โยนข้อยกเว้นหากมีการขัดจังหวะที่ร้องขอ.