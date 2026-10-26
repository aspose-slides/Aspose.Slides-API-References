---
title: IInterruptionToken
second_title: Aspose.Slides برای مرجع API جاوا
description: این کلاس توکنی را نشان می‌دهد که برای اعلام به‌کارهای طولانی‌مدت درباره درخواست قطع استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

این کلاس توکنی را نشان می‌دهد که برای اعلام به‌کارهای طولانی‌مدت درباره درخواست قطع استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | در صورتی که قطع درخواست شده باشد، true برمی‌گرداند. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | در صورتی که قطع درخواست شده باشد، یک استثنا پرتاب می‌کند. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

در صورتی که قطع درخواست شده باشد، true برمی‌گرداند.

**باز می‌گرداند:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

در صورتی که قطع درخواست شده باشد، یک استثنا پرتاب می‌کند.