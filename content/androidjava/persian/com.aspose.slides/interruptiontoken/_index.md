---
title: InterruptionToken
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: این کلاس نشان‌دهنده توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا مشخص شود آیا قطع‌نامه درخواست شده است یا خیر.
type: docs
url: /fa/com.aspose.slides/interruptiontoken/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

این کلاس نشان‌دهندهٔ توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا مشخص شود آیا قطع‌نامه درخواست شده است یا خیر.
## متدها

| متد | توضیح |
| --- | --- |
| [getNone()](#getNone--) | نمایانگر یک توکن قطع خالی. |
| [isInterruptionRequested()](#isInterruptionRequested--) | در صورتی که قطع‌نامه درخواست شده باشد، مقدار true را برمی‌گرداند. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | اگر قطع‌نامه درخواست شده باشد، یک استثنا را پرتاب می‌کند. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

نمایانگر یک توکن قطع خالی.

--------------------

عملیات طولانی‌مدت هرگز توسط [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) وقتی از این توکن استفاده می‌شود، قطع نخواهند شد.

**بازگرداندن:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

در صورتی که قطع‌نامه درخواست شده باشد، مقدار true را برمی‌گرداند.

**بازگرداندن:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

اگر قطع‌نامه درخواست شده باشد، یک استثنا را پرتاب می‌کند.