---
title: ContinueWith()
second_title: Aspose.Slides for C++ APIリファレンス
description: タスクが完了したときに実行される継続処理を作成します。
type: docs
weight: 118
url: /ja/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) メソッド

タスクが完了したときに実行される継続処理を作成します。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | このタスクが完了したときに実行されるアクション |

### 戻り値

TaskPtr 続行処理を表す新しいタスク

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) メソッド

タスクが完了したときに実行される継続処理を作成します。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TResult | タスク結果の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | このタスクが完了したときに結果を取得する関数 |

### 戻り値

RTaskPtr 続行処理を表す新しいタスク

## 参照

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* クラス [Task](../)
* クラス [Func](../../../system/func/)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)