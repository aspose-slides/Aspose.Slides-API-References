---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /vi/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Biểu diễn nguồn của [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getToken()](#getToken--) | Trả về token mới được ràng buộc vào [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) này. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu đã yêu cầu ngắt, false nếu không. |
| [interrupt()](#interrupt--) | Khởi tạo yêu cầu ngắt. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Trả về token mới được ràng buộc vào [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) này.

**Trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Trả về true nếu đã yêu cầu ngắt, false nếu không.

**Trả về:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Khởi tạo yêu cầu ngắt.