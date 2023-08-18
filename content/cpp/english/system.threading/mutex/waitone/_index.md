---
title: WaitOne()
second_title: Aspose.Slides for C++ API Reference
description: Locks mutex. Performs unlimited waiting if neccessary.
type: docs
weight: 53
url: /system.threading/mutex/waitone/
---
## Mutex::WaitOne() method


Locks mutex. Performs unlimited waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Return Value

Always returns true as it does not return until mutex is locked.

## Mutex::WaitOne(int) method


Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### Return Value

Returns true if mutex was locked or false if timeout exceeded.

## Mutex::WaitOne(TimeSpan) method


Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### Return Value

Returns true if mutex was locked or false if timeout exceeded.

## See Also

* Class [Mutex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)