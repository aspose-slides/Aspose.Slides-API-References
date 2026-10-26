---
title: WaitAll()
second_title: مرجع API Aspose.Slides برای C++
description: صبر می‌کند تا تمام هندل‌ها فعال شوند.
type: docs
weight: 1
url: /fa/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) متد

منتظر می‌ماند تا تمام handle‌ها فعال شوند.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle‌هایی که باید منتظر آن‌ها بود. |
| millisecondsTimeout | int | [Timeout](../../timeout/) برای انتظار، بر حسب میلی‌ثانیه؛ -1 به معنی انتظار بی‌نهایت، 0 به معنی بررسی و بازگشت، مقادیر مثبت زمان-پایان هستند. |

### مقدار بازگشت

در صورتی که همه handle‌ها فعال شوند true برمی‌گردد، در صورتی که زمان انتظار منقضی شود false برمی‌گردد.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) متد

منتظر می‌ماند تا تمام handle‌ها فعال شوند.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle‌هایی که باید منتظر آن‌ها بود. |
| timeout | [TimeSpan](../../../system/timespan/) | یک [System::TimeSpan](../../../system/timespan/) که تعداد میلی‌ثانیه‌های انتظار را نشان می‌دهد، یا یک [System::TimeSpan](../../../system/timespan/) که -1 میلی‌ثانیه برای انتظار نامحدود است. |

### مقدار بازگشت

در صورتی که همه handle‌ها فعال شوند true برمی‌گردد، در صورتی که زمان انتظار منقضی شود false برمی‌گردد.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) متد

منتظر می‌ماند تا تمام handle‌ها فعال شوند.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle‌هایی که باید منتظر آن‌ها بود. |

### مقدار بازگشت

زمانی که هر عنصر در waitHandles سیگنال دریافت کند true برمی‌گردد؛ در غیر این صورت متد هرگز برنمی‌گردد.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [WaitHandle](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)