---
title: Wait()
second_title: Aspose.Slides for C++ API 参考
description: 释放对象上的锁，并阻塞当前线程直到重新获取锁。如果指定的超时间隔已到，线程进入就绪队列。可选地在等待之前退出同步上下文的同步域，并在之后重新获取该域。未实现。
type: docs
weight: 53
url: /zh/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) 方法


释放对象上的锁，并阻塞当前线程直到重新获取锁。如果指定的超时间隔已到，线程进入就绪队列。可选地在等待之前退出同步上下文的同步域，并在之后重新获取该域。未实现。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) 方法


释放对象上的锁，并阻塞当前线程直到重新获取锁。如果指定的超时间隔已到，线程进入就绪队列。可选地在等待之前退出同步上下文的同步域，并在之后重新获取该域。未实现。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) 方法


释放对象上的锁，并阻塞当前线程直到重新获取锁。如果指定的超时间隔已到，线程进入就绪队列。未实现。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) 方法


释放对象上的锁，并阻塞当前线程直到重新获取锁。如果指定的超时间隔已到，线程进入就绪队列。未实现。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) 方法


释放对象上的锁，并阻塞当前线程直到重新获取锁 未实现。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Monitor](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* Library [Aspose.Slides](../../../)