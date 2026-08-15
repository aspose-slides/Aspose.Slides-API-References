---
title: FromCanceled()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個因指定的取消令牌而已取消完成的任務。
type: docs
weight: 118
url: /zh-hant/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) 函式

建立一個因指定的取消令牌而已取消完成的任務。

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 造成任務被取消的取消令牌。 |

### 返回值

已取消的任務。

## 另請參閱

* 型別別名 [TaskPtr](../../system/taskptr/)
* 類別 [CancellationToken](../../system.threading/cancellationtoken/)
* 命名空間 [System::Threading::Tasks](../)
* 程式庫 [Aspose.Slides](../../)