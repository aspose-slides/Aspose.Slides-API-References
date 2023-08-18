---
title: Timer()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Function to be called by the timer. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Function to be called by the timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Callback function argument. |
| dueTime | **int64_t** | [Timeout](../../timeout/) before first invocation of callback function, in milliseconds; negative values doesn't schedule timer after creation so it can be re-scheduled later. |
| period | **int64_t** | [Timeout](../../timeout/) between consequental invocations of callback function, in milliseconds; non-positive values mean that timer should only be executed once. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Function to be called by the timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Callback function argument. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) before first invocation of callback function; negative values doesn't schedule timer after creation so it can be re-scheduled later. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) between consequental invocations of callback function; non-positive values mean that timer should only be executed once. |

## See Also

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)