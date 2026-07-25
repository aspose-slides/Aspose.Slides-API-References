---
title: Start()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトのスケジューラを使用してタスクの実行を開始します。
type: docs
weight: 170
url: /ja/system.threading.tasks/task/start/
---
## Task::Start() メソッド

既定のスケジューラを使用してタスクの実行を開始します。

```cpp
void System::Threading::Tasks::Task::Start()
```

## Task::Start(const SharedPtr\<TaskScheduler\>\&) メソッド

指定されたスケジューラを使用してタスクの実行を開始します。

```cpp
void System::Threading::Tasks::Task::Start(const SharedPtr<TaskScheduler> &scheduler)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 実行に使用するスケジューラ |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Task](../)
* クラス [TaskScheduler](../../taskscheduler/)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)