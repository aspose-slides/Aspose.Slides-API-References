---
title: WaitAny()
second_title: Aspose.Slides برای مرجع API C++
description: صبر می‌کند تا هر یک از هندل‌ها فعال شوند.
type: docs
weight: 14
url: /fa/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) متد


صبر می‌کند تا هر یک از هندل‌ها فعال شوند.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | هندل‌هایی که باید منتظر آنها باشید. |
| millisecondsTimeout | int | [Timeout](../../timeout/) برای صبر کردن، به میلی‌ثانیه؛ -1 به معنی انتظار بی‌نهایت، 0 به معنی بررسی و بازگشت، مقادیر مثبت به عنوان زمان‌سپری‌های محدود هستند. |

### مقدار بازگشت

True اگر هر هندلی فعال شده باشد، false اگر زمان‌انتظار تمام شده باشد.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) متد


صبر می‌کند تا هر یک از هندل‌ها فعال شوند.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | هندل‌هایی که باید منتظر آنها باشید. |
| timeout | [TimeSpan](../../../system/timespan/) | یک [System::TimeSpan](../../../system/timespan/) که تعداد میلی‌ثانیه‌های انتظار را نشان می‌دهد، یا یک [System::TimeSpan](../../../system/timespan/) که -1 میلی‌ثانیه به معنی انتظار نامحدود است. |

### مقدار بازگشت

True اگر هر هندلی فعال شده باشد، false اگر زمان‌انتظار تمام شده باشد.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) متد


صبر می‌کند تا هر یک از هندل‌ها فعال شوند.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | هندل‌هایی که باید منتظر آنها باشید. |

### مقدار بازگشت

True زمانی که همهٔ عناصر در waitHandles سیگنال دریافت کرده باشند؛ در غیر این صورت متد هرگز بازگردانده نمی‌شود.

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [WaitHandle](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)