---
title: WaitOne()
second_title: Aspose.Slides برای C++ مرجع API
description: تا دورهٔ نامحدود منتظر می‌شود تا هندل فعال شود.
type: docs
weight: 27
url: /fa/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() متد

تا مدت نامحدود منتظر می‌ماند تا دستگیره فعال شود.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### مقدار بازگشت

همواره true را برمی‌گرداند زیرا هیچ‌وقت‌تایمی رخ نمی‌دهد.

## WaitHandle::WaitOne(int) متد

منتظر می‌ماند تا دستگیره فعال شود.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) برای انتظار، بر حسب میلی‌ثانیه؛ -1 به معنی انتظار نامحدود، 0 به معنی بررسی و بازگشت، مقادیر مثبت زمان‌سنجی هستند. |

### مقدار بازگشت

اگر دستگیره فعال شد true و اگر زمان‌سنجی تمام شد false برمی‌گرداند.

## WaitHandle::WaitOne(TimeSpan) متد

منتظر می‌ماند تا دستگیره فعال شود.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | یک [System::TimeSpan](../../../system/timespan/) که تعداد میلی‌ثانیه‌های انتظار را نمایان می‌کند، یا یک [System::TimeSpan](../../../system/timespan/) که نمایانگر -1 میلی‌ثانیه برای انتظار نامحدود است. |

### مقدار بازگشت

اگر دستگیره فعال شد true و اگر زمان‌سنجی تمام شد false برمی‌گرداند.

## WaitHandle::WaitOne(int, bool) متد

منتظر می‌ماند تا دستگیره فعال شود.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) برای انتظار، بر حسب میلی‌ثانیه؛ -1 به معنی انتظار نامحدود، 0 به معنی بررسی و بازگشت، مقادیر مثبت زمان‌سنجی هستند. |
| exitContext | **bool** | اگر true باشد، قبل از انتظار، قفل دستگیره باید آزاد شود. |

### مقدار بازگشت

اگر دستگیره فعال شد true و اگر زمان‌سنجی تمام شد false برمی‌گرداند.

## موارد مرتبط

* کلاس [WaitHandle](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضانام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)