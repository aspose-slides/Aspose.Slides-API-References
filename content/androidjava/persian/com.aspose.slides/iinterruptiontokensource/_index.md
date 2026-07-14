---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the source of .
type: docs
url: /fa/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

منبع [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) را نمایندگی می‌کند.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getToken()](#getToken--) | یک توکن جدید که به این [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) پیوسته است را برمی‌گرداند. |
| [isInterruptionRequested()](#isInterruptionRequested--) | اگر درخواست قطع شد مقدار true و در غیر این صورت false برمی‌گرداند. |
| [interrupt()](#interrupt--) | درخواست قطع را مقداردهی اولیه می‌کند. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


یک توکن جدید که به این [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) پیوسته است را برمی‌گرداند.

**بازگشت:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


اگر درخواست قطع شد مقدار true و در غیر این صورت false برمی‌گرداند.

**بازگشت:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


درخواست قطع را مقداردهی اولیه می‌کند.