---
title: WaitAny()
second_title: Aspose.Slides for C++ API Reference
description: Waits for any of the provided Task objects to complete execution.
type: docs
weight: 183
url: /system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function


Waits for any of the provided [Task](../task/) objects to complete execution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | An array of [Task](../task/) instances on which to wait. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A [CancellationToken](../../system.threading/cancellationtoken/) to observe while waiting for the tasks to complete. |

### Return Value

The index of the completed task in the tasks array.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function


Waits for any of the provided [Task](../task/) objects to complete execution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | An array of [Task](../task/) instances on which to wait. |

### Return Value

The index of the completed task in the tasks array.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)