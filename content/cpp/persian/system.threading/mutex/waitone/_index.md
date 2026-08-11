---
title: WaitOne()
second_title: Aspose.Slides برای C++ مرجع API
description: قفل می‌کند mutex. اگر ضروری باشد، انتظار نامحدود انجام می‌دهد.
type: docs
weight: 53
url: /fa/system.threading/mutex/waitone/
---
## Mutex::WaitOne() متد


قفل می‌کند mutex. اگر ضروری باشد، انتظار نامحدود انجام می‌دهد.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### مقدار برگشت

همیشه true را برمی‌گرداند زیرا تا وقتی که mutex قفل نشده، باز نمی‌گردد.

## Mutex::WaitOne(int) متد


قفل می‌کند mutex. اگر ضروری باشد، انتظار انجام می‌دهد.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsTimeout | int | زمان انتظار بر حسب میلی‌ثانیه. |

### مقدار برگشت

true برمی‌گرداند اگر mutex قفل شده باشد یا false اگر زمان‌انتظار بیش از حد باشد.

## Mutex::WaitOne(TimeSpan) متد


قفل می‌کند mutex. اگر ضروری باشد، انتظار انجام می‌دهد.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | یک [System::TimeSpan](../../../system/timespan/) که تعداد میلی‌ثانیه‌های انتظار را نشان می‌دهد، یا یک [System::TimeSpan](../../../system/timespan/) که -1 میلی‌ثانیه را برای انتظار نامحدود نشان می‌دهد. |

### مقدار برگشت

true برمی‌گرداند اگر mutex قفل شده باشد یا false اگر زمان‌انتظار بیش از حد باشد.

## موارد مرتبط

* کلاس [Mutex](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)