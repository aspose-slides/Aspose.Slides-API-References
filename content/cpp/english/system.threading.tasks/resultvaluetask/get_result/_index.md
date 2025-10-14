---
title: get_Result()
second_title: Aspose.Slides for C++ API Reference
description: Gets the result of the completed task.
type: docs
weight: 66
url: /system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() const method


Gets the result of the completed task.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result() const
```


### Return Value

T The result value.
## Remarks



If the task is backed by a ResultTask<T>, this method will await the result and cache it. Subsequent calls will return the cached value without awaiting. 

## See Also

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)