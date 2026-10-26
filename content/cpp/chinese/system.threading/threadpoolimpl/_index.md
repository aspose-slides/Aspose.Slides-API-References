---
title: ThreadPoolImpl
second_title: Aspose.Slides for C++ API 参考
description: 线程池内部数据。这是一种通过访问函数进行内存管理的单例类型。您不应直接创建其实例。
type: docs
weight: 235
url: /zh/system.threading/threadpoolimpl/
---
## ThreadPoolImpl 类


[Thread](../thread/) 池内部数据。 这是一种单例类型，内存管理由访问函数完成。您不应直接创建其实例。

```cpp
class ThreadPoolImpl
```

## 方法

| Method | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | 获取可用线程的数量。 |
| static **bool**\& [GetInitialized](./getinitialized/)() | 获取初始化状态单例。 |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | 获取并发线程的最大数量。 |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | 获取池创建的线程的最小数量。 |
| void [JoinAll](./joinall/)() | 加入所有拥有的线程。无限期等待。 |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | 向队列添加工作项。 |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | 设置池拥有的线程数量。 |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | 设置池拥有的最小线程数量。 |
|  [ThreadPoolImpl](./threadpoolimpl/)() | 构造函数。 |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | 析构函数。如果线程尚未结束，则等待所有线程。 |
## 另请参阅

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)