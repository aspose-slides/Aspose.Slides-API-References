---
title: IWarningInfo
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک رابط پایه برای تمام هشدارها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

یک رابط پایه برای تمام هشدارها را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | اگر receiver مقدار null نداشته باشد، هشدار را به receiver مشخص شده پایان می‌دهد و اگر receiver تصمیم به لغو عملیات بگیرد، AbortRequestedException را پرتاب می‌کند. |
| [getWarningType()](#getWarningType--) | نوعی از هشدار را برمی‌گرداند. |
| [getDescription()](#getDescription--) | یک توصیف قابل خواندن برای انسان از این هشدار را برمی‌گرداند. |

### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

اگر receiver مقدار null نداشته باشد، هشدار را به receiver مشخص شده پایان می‌دهد و اگر receiver تصمیم به لغو عملیات بگیرد، AbortRequestedException را پرتاب می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | شیء Receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

نوعی از هشدار را برمی‌گرداند. فقط-خواندنی [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**بازگشت:**
int

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

یک توصیف قابل خواندن برای انسان از این هشدار را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String