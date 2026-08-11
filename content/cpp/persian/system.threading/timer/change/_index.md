---
title: Change()
second_title: Aspose.Slides برای مرجع API C++
description: زمان‌سنج را دوباره برنامه‌ریزی یا لغو می‌کند.
type: docs
weight: 14
url: /fa/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) متد

زمان‌سنج را دوباره برنامه‌ریزی یا لغو می‌کند.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) قبل از فراخوانی بعدی تابع callback، به میلی‌ثانیه؛ مقادیر منفی زمان‌سنج را حتی اگر زمان‌بندی شده باشد لغو می‌کنند. |
| period | **int64_t** | [Timeout](../../timeout/) بین فراخوانی‌های متوالی تابع callback، به میلی‌ثانیه؛ مقادیر غیرمثبت به این معناست که زمان‌سنج فقط یک بار اجرا شود. |

## Timer::Change(System::TimeSpan, System::TimeSpan) متد

زمان‌سنج را دوباره برنامه‌ریزی یا لغو می‌کند.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) قبل از فراخوانی بعدی تابع callback؛ مقادیر منفی زمان‌سنج را حتی اگر زمان‌بندی شده باشد لغو می‌کنند. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) بین فراخوانی‌های متوالی تابع callback؛ مقادیر غیرمثبت به این معناست که زمان‌سنج فقط یک بار اجرا شود. |

## همچنین ببینید

* کلاس [Timer](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)