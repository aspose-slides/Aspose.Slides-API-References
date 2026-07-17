---
title: WaitAll()
second_title: Aspose.Slides for C++ API 参考
description: 等待所有提供的 Task 对象完成执行。
type: docs
weight: 170
url: /zh/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) 函数


等待所有提供的 [Task](../task/) 对象完成执行。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 实例数组。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 在等待任务完成期间要观察的 [CancellationToken](../../system.threading/cancellationtoken/)。 |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) 函数


等待所有提供的 [Task](../task/) 对象完成执行。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 实例数组。 |

## 另请参见

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* 类 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)