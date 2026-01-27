---
title: Run()
second_title: Aspose.Slides for C++ API Reference
description: Queues the specified work to run on the thread pool and returns a Task handle for that work.
type: docs
weight: 157
url: /system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) function


Queues the specified work to run on the thread pool and returns a [Task](../task/) handle for that work.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | The work to execute asynchronously. |

### Return Value

A [Task](../task/) that represents the work queued to execute in the thread pool.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) function


Queues the specified work to run on the thread pool and returns a [Task](../task/) handle for that work.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | The work to execute asynchronously. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A cancellation token that can be used to cancel the work if it has not yet started. |

### Return Value

A [Task](../task/) that represents the work queued to execute in the thread pool.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) function


Queues the specified work to run on the thread pool and returns a proxy for the [Task](../task/) returned by the function.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | The work to execute asynchronously, which returns a [Task](../task/). |

### Return Value

A [Task](../task/) that represents a proxy for the [Task](../task/) returned by the function.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) function


Queues the specified work to run on the thread pool and returns a Task<TResult> handle for that work.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | The type of the result returned by the task. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | The work to execute asynchronously. |

### Return Value

A Task<TResult> that represents the work queued to execute in the thread pool.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)