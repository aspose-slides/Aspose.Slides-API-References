---
title: "System::Threading::Tasks"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 1015
url: /zh-hant/system.threading.tasks/
---
## 類別

| Class | Description |
| --- | --- |
| [Parallel](./parallel/) | 提供平行迴圈和區域的支援。 |
| [ParallelLoopResult](./parallelloopresult/) | 提供 [Parallel](./parallel/) 迴圈的完成狀態。 |
| [ParallelOptions](./paralleloptions/) | 儲存設定，用於配置 [Parallel](./parallel/) 類別上方法的運作。 |
| [ResultTask](./resulttask/) | [Task](./task/) 的專門化，於完成時返回結果值。 |
| [ResultValueTask](./resultvaluetask/) | 表示一種混合任務類型，可包裝直接結果值或 ResultTask<T>。 |
| [Task](./task/) | 表示一個可等待且可與其他任務組合的非同步操作。 |
| [TaskScheduler](./taskscheduler/) | 表示一個負責將任務排入執行緒佇列的低階工作之物件。 |
| [ValueTask](./valuetask/) | 提供非同步操作的可等待結果。 |
## 函式

| Function | Description |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | 建立一個在時間延遲後完成的任務。 |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 建立一個在時間延遲後完成且可取消的任務。 |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | 建立一個因指定的 token 被取消而完成的任務。 |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 建立一個已以指定例外完成的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 建立一個已以指定例外和結果類型完成的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | 建立一個已成功完成且帶有指定結果的任務。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | 將指定的工作排入執行緒池執行，並回傳一個 [Task](./task/) 處理項目。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 將指定的工作排入執行緒池執行，並回傳一個 [Task](./task/) 處理項目。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | 將指定的工作排入執行緒池執行，並回傳一個指向該函式返回之 [Task](./task/) 的代理。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | 將指定的工作排入執行緒池執行，並回傳一個 Task<TResult> 處理項目。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 等待所有提供的 [Task](./task/) 物件完成執行。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 等待所有提供的 [Task](./task/) 物件完成執行。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 等待任一提供的 [Task](./task/) 物件完成執行。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 等待任一提供的 [Task](./task/) 物件完成執行。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 建立一個在所有提供的任務皆完成時結束的任務。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 建立一個在所有提供的任務皆完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 建立一個在所有提供的任務皆完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 建立一個在所有提供的任務皆完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 建立一個在任一提供的任務完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 建立一個在任一提供的任務完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 建立一個在任一提供的任務完成時結束的任務。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 建立一個在任一提供的任務完成時結束的任務。 |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | 建立一個可等待的任務，當等待時會非同步返回至目前的情境。 |
## 列舉

| Enum | Description |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |