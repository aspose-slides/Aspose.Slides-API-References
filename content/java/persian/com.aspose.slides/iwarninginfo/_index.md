---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /fa/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

نمایانگر یک رابط پایه برای تمام هشدارها است.
## متدها

| متد | توضیح |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | اگر receiver مقدار null نباشد، هشدار را به receiver مشخص شده پایان می‌دهد و اگر receiver تصمیم به لغو عملیات بگیرد AbortRequestedException را پرتاب می‌کند. |
| [getWarningType()](#getWarningType--) | یک نوع هشدار را برمی‌گرداند. |
| [getDescription()](#getDescription--) | یک توضیح خوانا برای این هشدار برمی‌گرداند. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


اگر receiver مقدار null نباشد، هشدار را به receiver مشخص شده پایان می‌دهد و اگر receiver تصمیم به لغو عملیات بگیرد AbortRequestedException را پرتاب می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | شیء Receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


یک نوع هشدار را برمی‌گرداند. فقط خواندنی [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**بازگشت:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


یک توضیح خوانا برای این هشدار را برمی‌گرداند. فقط خواندنی String.

**بازگشت:**
java.lang.String