---
title: TryEnter()
second_title: Aspose.Slides for C++ API Reference
description: Attempts to acquire an exclusive lock on the specified object Not implemented.
type: docs
weight: 27
url: /system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) method


Attempts to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) method


Attempts to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) method


Attempts, for the specified number of milliseconds, to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object Not implemented.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) method


Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)