---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: แสดงแหล่งที่มาของ .
type: docs
url: /th/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

แสดงแหล่งที่มาของ [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getToken()](#getToken--) | ส่งคืนโทเค็นใหม่ที่ผูกกับ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) นี้. |
| [isInterruptionRequested()](#isInterruptionRequested--) | ส่งคืนค่า true หากมีการขัดจังหวะ, false หากไม่ใช่. |
| [interrupt()](#interrupt--) | กำหนดคำขอขัดจังหวะ. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

ส่งคืนโทเค็นใหม่ที่ผูกกับ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) นี้.

**คืนค่า:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

ส่งคืนค่า true หากมีการขัดจังหวะ, false หากไม่ใช่.

**คืนค่า:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

กำหนดคำขอขัดจังหวะ.