---
title: WaitAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 提供された Task オブジェクトのいずれかが実行完了するまで待機します。
type: docs
weight: 183
url: /ja/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) 関数

提供された[Task](../task/)オブジェクトのいずれかが実行完了するまで待機します。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 待機対象となる[Task](../task/)インスタンスの配列です。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | タスクの完了を待機中に監視する[CancellationToken](../../system.threading/cancellationtoken/)です。 |

### 戻り値

tasks配列内で完了したタスクのインデックスです。

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) 関数

提供された[Task](../task/)オブジェクトのいずれかが実行完了するまで待機します。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 待機対象となる[Task](../task/)インスタンスの配列です。 |

### 戻り値

tasks配列内で完了したタスクのインデックスです。

## 参照

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* クラス [CancellationToken](../../system.threading/cancellationtoken/)
* 名前空間 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)