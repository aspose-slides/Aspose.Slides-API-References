---
title: Join()
second_title: Aspose.Slides for C++ API Reference
description: Joins managed thread. Performs unlimited waiting if required.
type: docs
weight: 196
url: /cpp/system.threading/thread/join/
---
## Thread::Join() method


Joins managed thread. Performs unlimited waiting if required.

```cpp
void System::Threading::Thread::Join()
```

## See Also

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Thread::Join(int) method


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### Return Value

True if thread was successfully joined, false if timeout exceeded.

## See Also

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Thread::Join([TimeSpan](../../../system/timespan/)) method


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [TimeSpan](../../../system/timespan/) set to the amount of time to wait for the thread to terminate. |

### Return Value

True if thread was successfully joined, false if timeout exceeded.

## See Also

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
