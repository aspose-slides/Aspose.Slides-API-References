---
title: RunSynchronously()
second_title: Aspose.Slides for C++ API 參考文件
description: 在當前執行緒上同步執行任務。
type: docs
weight: 157
url: /zh-hant/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() 方法


在當前執行緒上同步執行任務。

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```


## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) 方法


使用指定的排程器同步執行任務。

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
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