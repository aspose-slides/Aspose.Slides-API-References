---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Reference
description: Creates a continuation that executes when the task completes.
type: docs
weight: 105
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

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)