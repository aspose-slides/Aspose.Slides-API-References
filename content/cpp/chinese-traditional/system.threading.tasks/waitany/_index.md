---
title: WaitAny()
second_title: Aspose.Slides for C++ API 參考
description: 等待任意提供的 Task 物件完成執行。
type: docs
weight: 183
url: /zh-hant/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

等待任意提供的 [Task](../task/) 物件完成執行。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 實例陣列。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 在等待任務完成時觀察的 [CancellationToken](../../system.threading/cancellationtoken/)。 |

### 傳回值

已完成任務在 tasks 陣列中的索引。

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function

等待任意提供的 [Task](../task/) 物件完成執行。

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待的 [Task](../task/) 實例陣列。 |

### 傳回值

已完成任務在 tasks 陣列中的索引。

## 參見

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* 類別 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)