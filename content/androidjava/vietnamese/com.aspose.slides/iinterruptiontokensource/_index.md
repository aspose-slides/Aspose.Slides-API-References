---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn nguồn của .
type: docs
url: /vi/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Biểu diễn nguồn của [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Phương thức

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | Trả về token mới được ràng buộc với [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) này. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu đã yêu cầu ngắt quãng, false nếu không. |
| [interrupt()](#interrupt--) | Khởi tạo yêu cầu ngắt quãng. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Trả về token mới được ràng buộc với [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) này.

**Trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Trả về true nếu đã yêu cầu ngắt quãng, false nếu không.

**Trả về:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Khởi tạo yêu cầu ngắt quãng.