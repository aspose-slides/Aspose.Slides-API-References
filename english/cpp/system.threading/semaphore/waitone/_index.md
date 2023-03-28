---
title: WaitOne()
second_title: Aspose.Slides for C++ API Reference
description: Locks semaphore. Performs unlimited waiting if neccessary.
type: docs
weight: 40
url: /cpp/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method


Locks semaphore. Performs unlimited waiting if neccessary.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Return Value

Always returns true as it does not return until semaphore is locked.

## See Also

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Semaphore::WaitOne(int) method


Locks semaphore. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### Return Value

Returns true if semaphore was locked or false if timeout exceeded.

## See Also

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
