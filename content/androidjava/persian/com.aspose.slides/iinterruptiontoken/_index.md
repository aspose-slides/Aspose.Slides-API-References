---
title: IInterruptionToken
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: این کلاس نمایانگر توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا نشان دهد آیا قطع‌کردن درخواست شده است یا خیر.
type: docs
url: /fa/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

این کلاس نمایانگر توکنی است که برای علامت‌گذاری وظایف طولانی‌مدت استفاده می‌شود تا نشان دهد آیا قطع‌کردن درخواست شده است یا خیر.
## Methods

| Method | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | در صورتی که قطع‌کردن درخواست شده باشد، true برمی‌گرداند. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | اگر قطع‌کردن درخواست شده باشد، یک استثنا می‌اندازد. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


در صورتی که قطع‌کردن درخواست شده باشد، true برمی‌گرداند.

**بازمی‌گرداند:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


اگر قطع‌کردن درخواست شده باشد، یک استثنا می‌اندازد.