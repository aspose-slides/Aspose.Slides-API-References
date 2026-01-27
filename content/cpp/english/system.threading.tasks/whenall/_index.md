---
title: WhenAll()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that will complete when all of the supplied tasks have completed.
type: docs
weight: 196
url: /system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | The tasks to wait on for completion. |

### Return Value

A task that represents the completion of all of the supplied tasks.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | The tasks to wait on for completion. |

### Return Value

A task that represents the completion of all of the supplied tasks.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | The type of the completed tasks' results. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | The tasks to wait on for completion. |

### Return Value

A task that returns an array of all the results when all tasks complete.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | The type of the completed tasks' results. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | The tasks to wait on for completion. |

### Return Value

A task that returns an array of all the results when all tasks complete.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)