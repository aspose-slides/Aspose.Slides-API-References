---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Reference
description: Creates a continuation that executes when the task completes.
type: docs
weight: 118
url: /system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


Creates a continuation that executes when the task completes.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action to execute when this task completes |

### Return Value

TaskPtr A new task representing the continuation

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Creates a continuation that executes when the task completes.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | A type of task result |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function to get result when this task completes |

### Return Value

RTaskPtr A new task representing the continuation

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)