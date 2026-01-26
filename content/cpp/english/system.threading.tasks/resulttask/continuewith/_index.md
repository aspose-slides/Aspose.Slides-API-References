---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Reference
description: Creates a continuation that executes when the result task completes.
type: docs
weight: 40
url: /system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Creates a continuation that executes when the result task completes.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action to execute when this task completes, receiving this result task |

### Return Value

TaskPtr A new task representing the continuation
## Remarks



The continuation action receives this [ResultTask](../) to access the result value 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method


Creates a continuation that executes when the result task completes.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TNewResult | Result type of task continuation |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Function to get continuation result when this task completes, receiving this result task |

### Return Value

RTaskPtr A new task representing the continuation
## Remarks



The continuation function receives this [ResultTask](../) to access the result value 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method


Creates a continuation that executes when the task completes.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action to execute when this task completes |

### Return Value

TaskPtr A new task representing the continuation

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Creates a continuation that executes when the task completes.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | A type of task result |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function to get result when this task completes |

### Return Value

RTaskPtr A new task representing the continuation

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)