---
title: InterruptionTokenSource
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn nguồn của .
type: docs
url: /vi/com.aspose.slides/interruptiontokensource/
---
**Kế thừa:**
java.lang.Object
```
public class InterruptionTokenSource
```

Biểu diễn nguồn của [InterruptionToken](../../com.aspose.slides/interruptiontoken).
## Các phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Tạo một [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) mới. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getToken()](#getToken--) | Trả về token mới được liên kết với [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) này. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu đã yêu cầu ngắt, ngược lại trả về false. |
| [interrupt()](#interrupt--) | Khởi tạo yêu cầu ngắt. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


Tạo một [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) mới.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


Trả về token mới được liên kết với [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) này.

**Trả về:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Trả về true nếu đã yêu cầu ngắt, ngược lại trả về false.

**Trả về:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


Khởi tạo yêu cầu ngắt.