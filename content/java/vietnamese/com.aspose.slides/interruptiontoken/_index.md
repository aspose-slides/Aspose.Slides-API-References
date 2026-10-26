---
title: InterruptionToken
second_title: Tham chiếu API Aspose.Slides cho Java
description: Lớp này biểu thị token được sử dụng để báo hiệu các tác vụ chạy lâu liệu việc ngắt có được yêu cầu hay không.
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

Lớp này biểu thị token được sử dụng để báo hiệu các tác vụ chạy lâu liệu việc ngắt có được yêu cầu hay không.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getNone()](#getNone--) | Biểu thị một token ngắt rỗng. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu đã yêu cầu ngắt. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Ném một nếu đã yêu cầu ngắt. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Biểu thị một token ngắt rỗng.

--------------------

Các hoạt động chạy lâu sẽ không bao giờ bị ngắt thông qua [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) khi sử dụng token này.

**Trả về:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Trả về true nếu đã yêu cầu ngắt.

**Trả về:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Ném một nếu đã yêu cầu ngắt.