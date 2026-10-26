---
title: Start()
second_title: Aspose.Slides for C++ API 參考
description: 使用預設排程器啟動任務執行。
type: docs
weight: 170
url: /zh-hant/system.threading.tasks/task/start/
---
## Task::Start() 方法

使用預設排程器啟動任務執行。

```cpp
void System::Threading::Tasks::Task::Start()
```

## Task::Start(const SharedPtr\<TaskScheduler\>\&) 方法

使用指定的排程器啟動任務執行。

```cpp
void System::Threading::Tasks::Task::Start(const SharedPtr<TaskScheduler> &scheduler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 執行時使用的排程器 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Task](../)
* 類別 [TaskScheduler](../../taskscheduler/)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)