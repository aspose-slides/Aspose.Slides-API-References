---
title: FromException()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that has completed with a specified exception.
type: docs
weight: 131
url: /system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function


Creates a task that has completed with a specified exception.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | The exception with which to complete the task. |

### Return Value

A faulted task.

## System::Threading::Tasks::FromException(const Exception\&) function


Creates a task that has completed with a specified exception and result type.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | The type of the task's result. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | The exception with which to complete the task. |

### Return Value

A faulted task with the specified result type.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)