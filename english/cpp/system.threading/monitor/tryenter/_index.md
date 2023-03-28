---
title: TryEnter()
second_title: Aspose.Slides for C++ API Reference
description: Attempts to acquire an exclusive lock on the specified object Not implemented.
type: docs
weight: 27
url: /cpp/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&) method


Attempts to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Monitor::TryEnter(const [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, **bool**\&) method


Attempts to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Monitor::TryEnter(const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, **int32_t**) method


Attempts, for the specified number of milliseconds, to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Monitor::TryEnter(const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, [TimeSpan](../../../system/timespan/)) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Monitor::TryEnter(const [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, **int32_t**, **bool**\&) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## Monitor::TryEnter(const [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, [TimeSpan](../../../system/timespan/), **bool**\&) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
