---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Reference
description: Creates a continuation that executes when the result task completes.
type: docs
weight: 40
url: /system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Creates a continuation that executes when the result task completes.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action to execute when this task completes, receiving this result task |

### Return Value

TaskPtr A new task representing the continuation
## Remarks



The continuation action receives this [ResultTask](../) to access the result value 

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)