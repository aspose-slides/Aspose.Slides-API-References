---
title: Wait()
second_title: Aspose.Slides for C++ API Reference
description: Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Optionally exits the synchronization domain for the synchronized context before the wait and reacquires the domain afterward. Not implemented.
type: docs
weight: 53
url: /system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) method


Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Optionally exits the synchronization domain for the synchronized context before the wait and reacquires the domain afterward. Not implemented.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) method


Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Optionally exits the synchronization domain for the synchronized context before the wait and reacquires the domain afterward. Not implemented.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) method


Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Not implemented.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) method


Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Not implemented.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) method


Releases the lock on an object and blocks the current thread until it reacquires the lock Not implemented.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)