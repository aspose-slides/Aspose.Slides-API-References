---
title: InterruptionToken
second_title: Aspose.Slides برای مرجع API جاوا
description: این کلاس نمایانگر توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا مشخص کند آیا قطع درخواست شده است یا خیر.
type: docs
url: /fa/com.aspose.slides/interruptiontoken/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

این کلاس نمایانگر توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا مشخص شود آیا قطع درخواست شده است یا خیر.
## متدها

| متد | توضیح |
| --- | --- |
| [getNone()](#getNone--) | نمایانگر یک توکن قطع خالی است. |
| [isInterruptionRequested()](#isInterruptionRequested--) | اگر قطع درخواست شده باشد، مقدار true را برمی‌گرداند. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | اگر قطع درخواست شده باشد، یک استثنا می‌اندازد. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


نمایانگر یک توکن قطع خالی است.

--------------------

عملیات‌های طولانی‌مدت با استفاده از این توکن هرگز از طریق [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) قطع نخواهند شد.

**بازگرداندن:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


اگر قطع درخواست شده باشد، مقدار true را برمی‌گرداند.

**بازگرداندن:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


اگر قطع درخواست شده باشد، یک استثنا می‌اندازد.