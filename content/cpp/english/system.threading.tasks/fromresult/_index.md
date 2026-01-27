---
title: FromResult()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that has successfully completed with the specified result.
type: docs
weight: 144
url: /system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) function


Creates a task that has successfully completed with the specified result.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | The type of the task's result. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| result | TResult | The result value with which to complete the task. |

### Return Value

A successfully completed task.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)