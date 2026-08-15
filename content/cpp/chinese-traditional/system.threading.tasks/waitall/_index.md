---
title: WaitAll()
second_title: Aspose.Slides for C++ API 參考
description: 等待所有提供的 Task 物件完成執行。
type: docs
weight: 170
url: /zh-hant/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

等待所有提供的 [Task](../task/) 物件完成執行。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 實例陣列。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 在等待工作完成期間要觀察的 [CancellationToken](../../system.threading/cancellationtoken/)。 |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) function

等待所有提供的 [Task](../task/) 物件完成執行。

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 實例陣列。 |

## 另請參閱

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* 類別 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)