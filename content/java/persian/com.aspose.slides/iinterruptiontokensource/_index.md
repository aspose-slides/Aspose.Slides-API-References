---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /fa/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

منبع [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getToken()](#getToken--) | یک توکن جدید متصل به این [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) را برمی‌گرداند. |
| [isInterruptionRequested()](#isInterruptionRequested--) | اگر درخواست قطع شد، true را برمی‌گرداند؛ در غیر این صورت false. |
| [interrupt()](#interrupt--) | درخواست قطع را مقداردهی اولیه می‌کند. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

یک توکن جدید متصل به این [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) را برمی‌گرداند.

**بازگشت:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

اگر درخواست قطع شد، true را برمی‌گرداند؛ در غیر این صورت false.

**بازگشت:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

درخواست قطع را مقداردهی اولیه می‌کند.