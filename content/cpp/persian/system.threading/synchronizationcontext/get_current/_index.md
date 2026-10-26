---
title: get_Current()
second_title: Aspose.Slides برای مرجع API C++
description: زمینه همگام‌سازی را برای نخ جاری دریافت می‌کند.
type: docs
weight: 40
url: /fa/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() متد

SynchronizationContext جاری برای نخ فعلی را دریافت می‌کند.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### مقدار برگشتی

SharedPtr<SynchronizationContext> یک اشاره‌گر به اشتراک‌گذاری شده به SynchronizationContext نخ جاری.

## توضیحات

اگر برای نخ جاری هیچ SynchronizationContext تنظیم نشده باشد، null برمی‌گرداند.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [SynchronizationContext](../)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)