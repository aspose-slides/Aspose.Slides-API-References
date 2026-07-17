---
title: Timer()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor

构造函数。

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 计时器调用的函数。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor

构造函数。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 计时器调用的函数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回调函数的参数。 |
| dueTime | **int64_t** | [Timeout](../../timeout/) 第一次调用回调函数之前，以毫秒为单位；负值表示创建后不调度计时器，可稍后重新调度。 |
| period | **int64_t** | [Timeout](../../timeout/) 连续调用回调函数之间的间隔，以毫秒为单位；非正值表示计时器只执行一次。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor

构造函数。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 计时器调用的函数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回调函数的参数。 |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 第一次调用回调函数之前；负值表示创建后不调度计时器，可稍后重新调度。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 连续调用回调函数之间的间隔；非正值表示计时器只执行一次。 |

## 另请参阅

* 类型定义 [TimerCallback](../../timercallback/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Timer](../)
* 类 [Object](../../../system/object/)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)