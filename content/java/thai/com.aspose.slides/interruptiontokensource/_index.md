---
title: InterruptionTokenSource
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
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
## คอนสตรักเตอร์

| คอนสตรักเตอร์ | คำอธิบาย |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | สร้าง [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) ใหม่. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getToken()](#getToken--) | คืนโทเคนใหม่ที่ผูกไว้กับ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) นี้. |
| [isInterruptionRequested()](#isInterruptionRequested--) | คืนค่า true หากการขัดจังหวะถูกขอ, false ในกรณีอื่น. |
| [interrupt()](#interrupt--) | เริ่มการขอขัดจังหวะ. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


สร้าง [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) ใหม่.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


คืนโทเคนใหม่ที่ผูกไว้กับ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) นี้.

**คืนค่า:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


คืนค่า true หากการขัดจังหวะถูกขอ, false ในกรณีอื่น.

**คืนค่า:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


เริ่มการขอขัดจังหวะ.