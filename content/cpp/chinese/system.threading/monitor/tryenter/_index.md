---
title: TryEnter()
second_title: Aspose.Slides for C++ API 参考
description: 尝试获取对指定对象的排他锁 未实现。
type: docs
weight: 27
url: /zh/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) 方法

尝试获取对指定对象的排他锁 未实现。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) 方法

尝试获取对指定对象的排他锁，并原子性地设置一个指示锁是否已被获取的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) 方法

在指定的毫秒数内尝试获取对指定对象的排他锁 未实现。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) 方法


在指定的时间段内尝试获取对指定对象的排他锁 未实现。

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) 方法


在指定的时间段内尝试获取对指定对象的排他锁，并原子性地设置一个指示锁是否已被获取的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) 方法


在指定的时间段内尝试获取对指定对象的排他锁，并原子性地设置一个指示锁是否已被获取的值。

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Monitor](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* Library [Aspose.Slides](../../../)