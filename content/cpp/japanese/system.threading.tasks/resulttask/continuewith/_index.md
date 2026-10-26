---
title: ContinueWith()
second_title: Aspose.Slides for C++ API リファレンス
description: 結果タスクが完了したときに実行される継続を作成します。
type: docs
weight: 40
url: /ja/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) メソッド


結果タスクが完了したときに実行される継続を作成します。

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | このタスクが完了したときに実行されるアクションで、この結果タスクを受け取ります |

### 戻り値

TaskPtr 継続を表す新しいタスク
## 備考



継続アクションはこの [ResultTask](../) を受け取り、結果値にアクセスします。

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) メソッド


結果タスクが完了したときに実行される継続を作成します。

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TNewResult | タスク継続の結果型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | このタスクが完了したときに継続結果を取得する関数で、結果タスクを受け取ります |

### 戻り値

RTaskPtr 継続を表す新しいタスク
## 備考



継続関数はこの [ResultTask](../) を受け取り、結果値にアクセスします。

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) メソッド


タスクが完了したときに実行される継続を作成します。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | このタスクが完了したときに実行されるアクション |

### 戻り値

TaskPtr 継続を表す新しいタスク

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) メソッド


タスクが完了したときに実行される継続を作成します。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TResult | タスク結果の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | このタスクが完了したときに結果を取得する関数 |

### 戻り値

RTaskPtr 継続を表す新しいタスク

## 参照

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)