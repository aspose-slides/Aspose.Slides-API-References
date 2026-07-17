---
title: Delay()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个在时间延迟后完成的任务。
type: docs
weight: 105
url: /zh/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) 函数

创建一个在时间延迟后完成的任务。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 在完成返回的任务之前要等待的毫秒数，或 -1 表示无限期等待。 |

### 返回值

表示时间延迟的任务。

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) 函数

创建一个在时间延迟后完成且可以被取消的任务。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 在完成返回的任务之前要等待的毫秒数，或 -1 表示无限期等待。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 可用于取消延迟的取消令牌。 |

### 返回值

表示时间延迟的任务。

## 另见

* Typedef [TaskPtr](../../system/taskptr/)
* 类 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空间 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)