---
title: Change()
second_title: Aspose.Slides for C++ API Reference
description: Re-schedules or cancels timer.
type: docs
weight: 14
url: /cpp/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) method


Re-schedules or cancels timer.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) before next invocation of callback function, in milliseconds; negative values cancel timer even if it was scheduled. |
| period | **int64_t** | [Timeout](../../timeout/) between consequental invocations of callback function, in milliseconds; non-positive values mean that timer should only be executed once. |

## Timer::Change(System::TimeSpan, System::TimeSpan) method


Re-schedules or cancels timer.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) before next invocation of callback function; negative values cancel timer even if it was scheduled. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) between consequental invocations of callback function; non-positive values mean that timer should only be executed once. |

## See Also

* Class [Timer](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)