---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個在任務完成時執行的延續。
type: docs
weight: 118
url: /zh-hant/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) 方法

建立一個在任務完成時執行的延續。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 在此任務完成時執行的操作 |

### 傳回值

TaskPtr 代表此延續的新任務

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) 方法

建立一個在任務完成時執行的延續。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| TResult | 任務結果的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | 在此任務完成時取得結果的函式 |

### 傳回值

RTaskPtr 代表此延續的新任務

## 另請參閱

* 型別別名 [TaskPtr](../../../system/taskptr/)
* 型別別名 [Action](../../../system/action/)
* 型別別名 [RTaskPtr](../../../system/rtaskptr/)
* 類別 [Task](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)