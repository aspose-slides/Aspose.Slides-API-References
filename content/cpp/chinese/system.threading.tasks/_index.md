---
title: "System::Threading::Tasks"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 1015
url: /zh/system.threading.tasks/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Parallel](./parallel/) | 提供对并行循环和区域的支持。 |
| [ParallelLoopResult](./parallelloopresult/) | 提供 [Parallel](./parallel/) 循环的完成状态。 |
| [ParallelOptions](./paralleloptions/) | 存储配置 [Parallel](./parallel/) 类上方法操作的选项。 |
| [ResultTask](./resulttask/) | 返回完成后结果值的 [Task](./task/) 特化。 |
| [ResultValueTask](./resultvaluetask/) | 表示一种混合任务类型，可以包装直接结果值或 ResultTask<T>。 |
| [Task](./task/) | 表示可以等待并与其他任务组合的异步操作。 |
| [TaskScheduler](./taskscheduler/) | 表示处理将任务排入线程队列的底层工作的对象。 |
| [ValueTask](./valuetask/) | 提供异步操作的可等待结果。 |
## 函数

| 函数 | 描述 |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | 创建一个在时间延迟后完成的任务。 |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 创建一个在时间延迟后完成且可取消的任务。 |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | 创建一个因使用指定令牌而被取消而完成的任务。 |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 创建一个以指定异常完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 创建一个以指定异常和结果类型完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | 创建一个已成功完成并带有指定结果的任务。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | 将指定工作排入线程池运行，并返回该工作的 [Task](./task/) 句柄。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 将指定工作排入线程池运行，并返回该工作的 [Task](./task/) 句柄。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | 将指定工作排入线程池运行，并返回函数返回的 [Task](./task/) 的代理。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | 将指定工作排入线程池运行，并返回该工作对应的 Task<TResult> 句柄。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 等待所有提供的 [Task](./task/) 对象完成执行。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 等待所有提供的 [Task](./task/) 对象完成执行。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 等待提供的任意 [Task](./task/) 对象完成执行。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 等待提供的任意 [Task](./task/) 对象完成执行。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 创建一个在所有提供的任务完成后完成的任务。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 创建一个在所有提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 创建一个在所有提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 创建一个在所有提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 创建一个在任意提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 创建一个在任意提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 创建一个在任意提供的任务完成后完成的任务。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 创建一个在任意提供的任务完成后完成的任务。 |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | 创建一个可等待的任务，在等待时异步返回到当前上下文。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |