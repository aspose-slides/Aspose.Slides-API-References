---
title: WhenAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたタスクのいずれかが完了したときに完了するタスクを作成します。
type: docs
weight: 209
url: /ja/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\) 関数

指定されたタスクのいずれかが完了したときに完了するタスクを作成します。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 完了を待つタスクです。 |

### 戻り値

指定されたタスクのうちのひとつの完了を表すタスクです。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) 関数

指定されたタスクのいずれかが完了したときに完了するタスクを作成します。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 完了を待つタスクです。 |

### 戻り値

指定されたタスクのうちのひとつの完了を表すタスクです。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 関数

指定されたタスクのいずれかが完了したときに完了するタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TResult | 完了したタスクの結果の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 完了を待つタスクです。 |

### 戻り値

任意のタスクが完了したときに、最初に完了したタスクを返すタスクです。

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\) 関数

指定されたタスクのいずれかが完了したときに完了するタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TResult | 完了したタスクの結果の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 完了を待つタスクです。 |

### 戻り値

任意のタスクが完了したときに、最初に完了したタスクを返すタスクです。

## 参照

* 型定義 [RTaskPtr](../../system/rtaskptr/)
* 型定義 [TaskPtr](../../system/taskptr/)
* 型定義 [SharedPtr](../../system/sharedptr/)
* 型定義 [ArrayPtr](../../system/arrayptr/)
* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)