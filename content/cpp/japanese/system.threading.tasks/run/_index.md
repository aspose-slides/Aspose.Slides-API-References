---
title: Run()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された作業をスレッドプールで実行するようキューに入れ、その作業のための Task ハンドルを返します。
type: docs
weight: 157
url: /ja/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) 関数

指定された作業をスレッドプールで実行するようキューに入れ、その作業のための [Task](../task/) ハンドルを返します。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 非同期で実行される作業。 |

### 戻り値

スレッドプールで実行されるようキューに入れられた作業を表す [Task](../task/)。

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) 関数

指定された作業をスレッドプールで実行するようキューに入れ、その作業のための [Task](../task/) ハンドルを返します。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 非同期で実行される作業。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 作業がまだ開始されていない場合に作業をキャンセルできるキャンセルトークン。 |

### 戻り値

スレッドプールで実行されるようキューに入れられた作業を表す [Task](../task/)。

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) 関数

指定された作業をスレッドプールで実行するようキューに入れ、関数が返す [Task](../task/) のプロキシを返します。

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | 非同期で実行される作業で、[Task](../task/) を返します。 |

### 戻り値

関数が返す [Task](../task/) のプロキシを表す [Task](../task/)。

## System::Threading::Tasks::Run(const Func\<TResult\>\&) 関数

指定された作業をスレッドプールで実行するようキューに入れ、その作業のための Task<TResult> ハンドルを返します。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TResult | タスクが返す結果の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | 非同期で実行される作業。 |

### 戻り値

スレッドプールで実行されるようキューに入れられた作業を表す Task<TResult>。

## 参照

* 型定義 [TaskPtr](../../system/taskptr/)
* 型定義 [Action](../../system/action/)
* 型定義 [RTaskPtr](../../system/rtaskptr/)
* クラス [CancellationToken](../../system.threading/cancellationtoken/)
* クラス [Func](../../system/func/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)