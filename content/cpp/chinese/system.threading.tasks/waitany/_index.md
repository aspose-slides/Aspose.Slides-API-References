---
title: WaitAny()
second_title: Aspose.Slides for C++ API 参考
description: 等待提供的任意 Task 对象完成执行。
type: docs
weight: 183
url: /zh/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) 函数

等待提供的任意 [Task](../task/) 对象完成执行。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 实例数组。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 在等待任务完成时要观察的 [CancellationToken](../../system.threading/cancellationtoken/)。 |

### 返回值

已完成任务在 tasks 数组中的索引。

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) 函数

等待提供的任意 [Task](../task/) 对象完成执行。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 实例数组。 |

### 返回值

已完成任务在 tasks 数组中的索引。

## 另见

* 类型别名 [ArrayPtr](../../system/arrayptr/)
* 类型别名 [TaskPtr](../../system/taskptr/)
* 类 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)