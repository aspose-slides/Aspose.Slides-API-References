---
title: WhenAll()
second_title: Aspose.Slides for C++ API リファレンス
description: すべての提供されたタスクが完了したときに完了するタスクを作成します。
type: docs
weight: 196
url: /ja/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) 関数


すべての提供されたタスクが完了したときに完了するタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 完了を待機するタスクです。 |

### 戻り値

提供されたすべてのタスクの完了を表すタスクです。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 関数


すべての提供されたタスクが完了したときに完了するタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 完了を待機するタスクです。 |

### 戻り値

提供されたすべてのタスクの完了を表すタスクです。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 関数


すべての提供されたタスクが完了したときに完了するタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TResult | 完了したタスクの結果の型です。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 完了を待機するタスクです。 |

### 戻り値

すべてのタスクが完了したときに、すべての結果の配列を返すタスクです。

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 関数


すべての提供されたタスクが完了したときに完了するタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TResult | 完了したタスクの結果の型です。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 完了を待機するタスクです。 |

### 戻り値

すべてのタスクが完了したときに、すべての結果の配列を返すタスクです。

## 参照

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)