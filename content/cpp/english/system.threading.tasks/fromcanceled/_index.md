---
title: FromCanceled()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that has completed due to cancellation with the specified token.
type: docs
weight: 118
url: /system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) function


Creates a task that has completed due to cancellation with the specified token.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | The cancellation token that caused the task to be cancelled. |

### Return Value

A cancelled task.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)