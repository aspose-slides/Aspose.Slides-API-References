---
title: RunSynchronously()
second_title: Aspose.Slides for C++ API Reference
description: Runs the task synchronously on the current thread.
type: docs
weight: 157
url: /system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() method


Runs the task synchronously on the current thread.

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```


### Exceptions

| Exception | Description |
| --- | --- |
| If | the task has already been started or completed |


## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>&) method


Runs the task synchronously using the specified scheduler.

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>& | The scheduler to use for execution |

### Exceptions

| Exception | Description |
| --- | --- |
| If | the task has already been started or completed |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [TaskScheduler](../../taskscheduler/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)