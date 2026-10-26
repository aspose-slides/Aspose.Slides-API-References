---
title: InterruptionTokenSource
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: แสดงถึงแหล่งที่มาของ .
type: docs
url: /th/com.aspose.slides/interruptiontokensource/
---
**การสืบทอด:**  
java.lang.Object  
```
public class InterruptionTokenSource
```

แสดงถึงแหล่งที่มาของ [InterruptionToken](../../com.aspose.slides/interruptiontoken).

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | สร้างใหม่ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getToken()](#getToken--) | คืนค่าโทเคนใหม่ที่ผูกกับ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) นี้. |
| [isInterruptionRequested()](#isInterruptionRequested--) | คืนค่า true หากมีการร้องขอการขัดจังหวะ, มิฉะนั้นจะคืนค่า false. |
| [interrupt()](#interrupt--) | เริ่มการร้องขอการขัดจังหวะ. |

### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

สร้างใหม่ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

คืนค่าโทเคนใหม่ที่ผูกกับ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) นี้.

**คืนค่า:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

คืนค่า true หากมีการร้องขอการขัดจังหวะ, มิฉะนั้นจะคืนค่า false.

**คืนค่า:**  
boolean

### interrupt() {#interrupt--}
```
public final void interrupt()
```

เริ่มการร้องขอการขัดจังหวะ.