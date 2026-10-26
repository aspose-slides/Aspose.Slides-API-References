---
title: WaitAll()
second_title: Aspose.Slides for C++ API リファレンス
description: 提供された Task オブジェクトがすべて実行完了するまで待機します。
type: docs
weight: 170
url: /ja/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) 関数

提供された [Task](../task/) オブジェクトがすべて実行完了するのを待ちます。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 待機対象となる [Task](../task/) インスタンスの配列。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | タスクが完了するまで監視する [CancellationToken](../../system.threading/cancellationtoken/)。 |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) 関数

提供された [Task](../task/) オブジェクトがすべて実行完了するのを待ちます。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 待機対象となる [Task](../task/) インスタンスの配列。 |

## 参照

* 型定義 [ArrayPtr](../../system/arrayptr/)
* 型定義 [TaskPtr](../../system/taskptr/)
* クラス [CancellationToken](../../system.threading/cancellationtoken/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)