---
title: WaitAll()
second_title: Aspose.Slides for C++ API Reference
description: Waits for all of the provided Task objects to complete execution.
type: docs
weight: 170
url: /system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function


Waits for all of the provided [Task](../task/) objects to complete execution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | An array of [Task](../task/) instances on which to wait. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A [CancellationToken](../../system.threading/cancellationtoken/) to observe while waiting for the tasks to complete. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) function


Waits for all of the provided [Task](../task/) objects to complete execution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | An array of [Task](../task/) instances on which to wait. |

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)