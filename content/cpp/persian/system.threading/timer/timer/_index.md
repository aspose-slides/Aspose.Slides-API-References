---
title: Timer()
second_title: Aspose.Slides برای C++ مرجع API
description: سازنده.
type: docs
weight: 1
url: /fa/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) سازنده

سازنده.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | تابعی که توسط زمان‌ساز فراخوانی می‌شود. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) سازنده

سازنده.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | تابعی که توسط زمان‌ساز فراخوانی می‌شود. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | آرگومان تابع بازگشت‌صدا. |
| dueTime | **int64_t** | [Timeout](../../timeout/) قبل از اولین فراخوانی تابع بازگشت‌صدا، بر حسب میلی‌ثانیه؛ مقادیر منفی پس از ایجاد زمان‌ساز برنامه‌ریزی نمی‌شوند تا بتوانند بعدا دوباره برنامه‌ریزی شوند. |
| period | **int64_t** | [Timeout](../../timeout/) بین فراخوانی‌های متوالی تابع بازگشت‌صدا، بر حسب میلی‌ثانیه؛ مقادیر صفر یا منفی به این معنی است که زمان‌ساز فقط یک بار اجرا می‌شود. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) سازنده

سازنده.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | تابعی که توسط زمان‌ساز فراخوانی می‌شود. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | آرگومان تابع بازگشت‌صدا. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) قبل از اولین فراخوانی تابع بازگشت‌صدا؛ مقادیر منفی پس از ایجاد زمان‌ساز برنامه‌ریزی نمی‌شوند تا بتوانند بعدا دوباره برنامه‌ریزی شوند. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) بین فراخوانی‌های متوالی تابع بازگشت‌صدا؛ مقادیر صفر یا منفی به این معنی است که زمان‌ساز فقط یک بار اجرا می‌شود. |

## موارد مرتبط

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Timer](../)
* کلاس [Object](../../../system/object/)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Threading](../../)
* Library [Aspose.Slides](../../../)