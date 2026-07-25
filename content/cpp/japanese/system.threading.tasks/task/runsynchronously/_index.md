---
title: RunSynchronously()
second_title: Aspose.Slides for C++ API リファレンス
description: タスクを現在のスレッドで同期的に実行します。
type: docs
weight: 157
url: /ja/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() メソッド


現在のスレッドでタスクを同期的に実行します。

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```


## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) メソッド


指定したスケジューラを使用してタスクを同期的に実行します。

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 実行に使用するスケジューラ |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Task](../)
* クラス [TaskScheduler](../../taskscheduler/)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)