---
title: Change()
second_title: Aspose.Slides C++ API 参考
description: 重新调度或取消计时器。
type: docs
weight: 14
url: /zh/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) 方法

重新调度或取消计时器。

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) 在下次调用回调函数之前，以毫秒为单位；负值会取消计时器，即使它已经被调度。 |
| period | **int64_t** | [Timeout](../../timeout/) 在连续调用回调函数之间，以毫秒为单位；非正值表示计时器只会执行一次。 |

## Timer::Change(System::TimeSpan, System::TimeSpan) 方法

重新调度或取消计时器。

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在下次调用回调函数之前；负值会取消计时器，即使它已经被调度。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在连续调用回调函数之间；非正值表示计时器只会执行一次。 |

## 另请参阅

* 类 [Timer](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)