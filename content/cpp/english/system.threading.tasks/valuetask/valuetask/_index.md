---
title: ValueTask()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an empty, uninitialized ValueTask.
type: docs
weight: 1
url: /system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructor


Constructs an empty, uninitialized [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Remarks



The task is not completed and contains no result. Attempting to get the result will throw an exception. 

## ValueTask::ValueTask(const TaskPtr\&) constructor


Constructs a [ValueTask](../) from a shared pointer to a [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | The task to wrap. Can be null for an empty task. |
## Remarks



The [ValueTask](../) will represent the state of the provided task. 

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)