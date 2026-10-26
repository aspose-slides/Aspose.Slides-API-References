---
title: AsTask()
second_title: Aspose.Slides for C++ API 參考文件
description: 將此 ResultValueTask 轉換為指向 ResultTask<T> 的共享指標。
type: docs
weight: 79
url: /zh-hant/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const 方法


將此 [ResultValueTask](../) 轉換為指向 ResultTask<T> 的共享指標。

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### 回傳值

RTaskPtr<T> 表示此操作的指向 ResultTask<T> 的共享指標。

## 備註



如果 [ResultValueTask](../) 包含直接結果，則會建立一個帶有該結果的已完成任務。若它包含任務，則回傳指向該任務的共享指標。 

## 另見

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)