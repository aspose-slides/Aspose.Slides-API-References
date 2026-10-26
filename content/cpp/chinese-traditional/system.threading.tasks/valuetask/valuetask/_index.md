---
title: ValueTask()
second_title: Aspose.Slides C++ API 參考
description: 建構一個空的、未初始化的 ValueTask。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() 建構子

建構一個空的、未初始化的 [ValueTask](../)。

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## 備註

此任務尚未完成，且不包含結果。嘗試取得結果將拋出例外。

## ValueTask::ValueTask(const TaskPtr\&) 建構子

從指向 [Task](../../task/) 的共享指標建構 [ValueTask](../)。

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | 要封裝的任務。空任務時可為 null。 |

## 備註

[ValueTask](../) 會表示提供之任務的狀態。

## 參閱

* 型別定義 [TaskPtr](../../../system/taskptr/)
* 類別 [ValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)