---
title: "System::Threading::Tasks"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 1015
url: /ja/system.threading.tasks/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Parallel](./parallel/) | 並列ループと領域のサポートを提供します。 |
| [ParallelLoopResult](./parallelloopresult/) | [Parallel](./parallel/) ループの完了状態を提供します。 |
| [ParallelOptions](./paralleloptions/) | [Parallel](./parallel/) クラスのメソッドの動作を構成するオプションを格納します。 |
| [ResultTask](./resulttask/) | [Task](./task/) の特殊化で、完了時に結果値を返します。 |
| [ResultValueTask](./resultvaluetask/) | 直接の結果値または ResultTask<T> のいずれかをラップできるハイブリッドタスク型を表します。 |
| [Task](./task/) | await 可能で他のタスクと合成できる非同期操作を表します。 |
| [TaskScheduler](./taskscheduler/) | タスクをスレッドにキューイングする低レベルの処理を扱うオブジェクトを表します。 |
| [ValueTask](./valuetask/) | 非同期操作の await 可能な結果を提供します。 |

## 関数

| 関数 | 説明 |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | 遅延時間の後に完了するタスクを作成します。 |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 遅延時間の後に完了し、キャンセルできるタスクを作成します。 |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | 指定されたトークンでキャンセルされたために完了したタスクを作成します。 |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 指定された例外で完了したタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 指定された例外と結果型で完了したタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | 指定された結果で正常に完了したタスクを作成します。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | 指定された作業をスレッドプールで実行するようキューイングし、その作業の [Task](./task/) ハンドルを返します。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 指定された作業をスレッドプールで実行するようキューイングし、その作業の [Task](./task/) ハンドルを返します。 |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | 指定された作業をスレッドプールで実行するようキューイングし、関数が返す [Task](./task/) のプロキシを返します。 |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | 指定された作業をスレッドプールで実行するようキューイングし、その作業の Task<TResult> ハンドルを返します。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 提供されたすべての [Task](./task/) オブジェクトが実行を完了するのを待機します。 |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 提供されたすべての [Task](./task/) オブジェクトが実行を完了するのを待機します。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 提供された任意の [Task](./task/) オブジェクトが実行を完了するのを待機します。 |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 提供された任意の [Task](./task/) オブジェクトが実行を完了するのを待機します。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | すべての提供されたタスクが完了したときに完了するタスクを作成します。 |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | すべての提供されたタスクが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | すべての提供されたタスクが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | すべての提供されたタスクが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 提供されたタスクのいずれかが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 提供されたタスクのいずれかが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 提供されたタスクのいずれかが完了したときに完了するタスクを作成します。 |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 提供されたタスクのいずれかが完了したときに完了するタスクを作成します。 |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | await されたときに、非同期で現在のコンテキストに制御を戻す await 可能なタスクを作成します。 |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |