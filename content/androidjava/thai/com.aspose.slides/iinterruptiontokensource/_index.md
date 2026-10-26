---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นตัวแทนของแหล่งที่มาของ .
type: docs
url: /th/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

เป็นตัวแทนของแหล่งที่มาของ [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getToken()](#getToken--) | ส่งคืนโทเค็นใหม่ที่ผูกกับ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) นี้. |
| [isInterruptionRequested()](#isInterruptionRequested--) | ส่งคืนค่า true หากมีการขัดจังหวะ, false หากไม่เป็นเช่นนั้น. |
| [interrupt()](#interrupt--) | เริ่มต้นการขอการขัดจังหวะ. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

ส่งคืนโทเค็นใหม่ที่ผูกกับ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) นี้.

**ส่งคืน:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

ส่งคืนค่า true หากมีการขัดจังหวะ, false หากไม่เป็นเช่นนั้น.

**ส่งคืน:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

เริ่มต้นการขอการขัดจังหวะ.