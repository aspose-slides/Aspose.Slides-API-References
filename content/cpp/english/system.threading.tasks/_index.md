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
| [ResultTask](./resulttask/) | A [Task](./task/) specialization that returns a result value upon completion. |
| [ResultValueTask](./resultvaluetask/) | Represents a hybrid task-like type that can wrap either a direct result value or a ResultTask<T>. |
| [Task](./task/) | Represents an asynchronous operation that can be awaited and composed with other tasks. |
| [TaskScheduler](./taskscheduler/) | Represents an object that handles the low-level work of queuing tasks onto threads. |
| [ValueTask](./valuetask/) | Provides an awaitable result of an asynchronous operation. |
## Functions

| Function | Description |
| --- | --- |
| void [DispatchCurrentContext](./dispatchcurrentcontext/)() | Dispatches all tasks bound to this thread synchronously. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Creates a task that completes after a time delay. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) |  |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) |  |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) |  |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) |  |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) |  |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) |  |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) |  |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) |  |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) |  |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) |  |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<T\>\> [WhenAll](./whenall/)([SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<T\>\>\>) |  |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<T\>\> [WhenAll](./whenall/)([ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<T\>\>) |  |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() |  |
## Enums

| Enum | Description |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |
