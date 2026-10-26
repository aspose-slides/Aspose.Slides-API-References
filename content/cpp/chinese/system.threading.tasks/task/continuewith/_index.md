---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个在任务完成时执行的延续。
type: docs
weight: 118
url: /zh/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) 方法

创建一个在任务完成时执行的延续。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 当此任务完成时要执行的 Action |

### 返回值

TaskPtr 表示该延续的新任务

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) 方法

创建一个在任务完成时执行的延续。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | TResult 任务结果的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | 当此任务完成时获取结果的 Function |

### 返回值

RTaskPtr 表示该延续的新任务

## 另见

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)