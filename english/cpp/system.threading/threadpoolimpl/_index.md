---
title: ThreadPoolImpl
second_title: Aspose.Slides for C++ API Reference
description: Thread pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.
type: docs
weight: 183
url: /cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Methods

| Method | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Gets number of available threads. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Gets initialization state singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Gets maximal number of concurrent threads. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Gets minimal number of threads being created by pool. |
| void [JoinAll](./joinall/)() | Joins all owned threads. Waits infinitely. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Adds work item to queue. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Sets number of threads owned by pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Sets minimal number of threads owned by pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Joins all threads if they were not terminated yet. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)