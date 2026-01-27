---
title: "System::Threading::Tasks"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 989
url: /system.threading.tasks/
---



## Classes

| Class | Description |
| --- | --- |
| [Parallel](./parallel/) | Provides support for parallel loops and regions. |
| [ParallelLoopResult](./parallelloopresult/) | Provides completion status of a [Parallel](./parallel/) loop. |
| [ParallelOptions](./paralleloptions/) | Stores options that configure the operation of methods on the [Parallel](./parallel/) class. |
| [ResultTask](./resulttask/) | A [Task](./task/) specialization that returns a result value upon completion. |
| [ResultValueTask](./resultvaluetask/) | Represents a hybrid task-like type that can wrap either a direct result value or a ResultTask<T>. |
| [Task](./task/) | Represents an asynchronous operation that can be awaited and composed with other tasks. |
| [TaskScheduler](./taskscheduler/) | Represents an object that handles the low-level work of queuing tasks onto threads. |
| [ValueTask](./valuetask/) | Provides an awaitable result of an asynchronous operation. |
## Functions

| Function | Description |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Creates a task that completes after a time delay. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Creates a task that completes after a time delay and can be cancelled. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Creates a task that has completed due to cancellation with the specified token. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Creates a task that has completed with a specified exception. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Creates a task that has completed with a specified exception and result type. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Creates a task that has successfully completed with the specified result. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Queues the specified work to run on the thread pool and returns a [Task](./task/) handle for that work. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Queues the specified work to run on the thread pool and returns a [Task](./task/) handle for that work. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Queues the specified work to run on the thread pool and returns a proxy for the [Task](./task/) returned by the function. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Queues the specified work to run on the thread pool and returns a Task<TResult> handle for that work. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Waits for all of the provided [Task](./task/) objects to complete execution. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Waits for all of the provided [Task](./task/) objects to complete execution. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Waits for any of the provided [Task](./task/) objects to complete execution. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Waits for any of the provided [Task](./task/) objects to complete execution. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Creates a task that will complete when all of the supplied tasks have completed. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Creates a task that will complete when all of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Creates a task that will complete when all of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Creates a task that will complete when all of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Creates a task that will complete when any of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Creates a task that will complete when any of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Creates a task that will complete when any of the supplied tasks have completed. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Creates a task that will complete when any of the supplied tasks have completed. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Creates an awaitable task that asynchronously yields back to the current context when awaited. |
## Enums

| Enum | Description |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
