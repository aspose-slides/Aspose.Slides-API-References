---
title: WaitOne()
second_title: Aspose.Slides for C++ API Reference
description: Waits for the handle to fire for unlimited period.
type: docs
weight: 27
url: /cpp/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


Waits for the handle to fire for unlimited period.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Return Value

Always returns true as no timeout occurs.

## WaitHandle::WaitOne(int) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |

### Return Value

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(TimeSpan) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### Return Value

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(int, bool) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |
| exitContext | **bool** | If true, waiting should drop the lock on the handle before waiting for it. |

### Return Value

True if handle fired, false if timeout exceeded.

## See Also

* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)