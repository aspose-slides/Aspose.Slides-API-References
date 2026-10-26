---
title: InterruptionToken
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp này biểu diễn token được sử dụng để báo hiệu các tác vụ chạy lâu thời gian yêu cầu ngắt hay không.
type: docs
url: /vi/com.aspose.slides/interruptiontoken/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Lớp này biểu diễn token được sử dụng để báo hiệu các tác vụ chạy lâu thời gian yêu cầu ngắt hay không.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getNone()](#getNone--) | Biểu diễn một token ngắt trống. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu việc ngắt đã được yêu cầu. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Ném một ngoại lệ nếu việc ngắt đã được yêu cầu. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Biểu diễn một token ngắt trống.

--------------------

Các hoạt động chạy lâu sẽ không bao giờ bị ngắt qua [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) khi sử dụng token này.

**Trả về:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Trả về true nếu việc ngắt đã được yêu cầu.

**Trả về:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Ném một ngoại lệ nếu việc ngắt đã được yêu cầu.