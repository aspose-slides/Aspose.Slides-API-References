---
title: AsTask()
second_title: Aspose.Slides for C++ API Reference
description: Converts this ResultValueTask to a shared pointer to ResultTask<T>.
type: docs
weight: 79
url: /system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const method


Converts this [ResultValueTask](../) to a shared pointer to ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Return Value

RTaskPtr<T> A shared pointer to a ResultTask<T> that represents this operation.
## Remarks



If the [ResultValueTask](../) contains a direct result, creates a completed task with that result. If it contains a task, returns a shared pointer to that task. 

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)