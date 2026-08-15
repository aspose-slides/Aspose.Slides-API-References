---
title: FromException()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個已完成且帶有指定例外的任務。
type: docs
weight: 131
url: /zh-hant/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) 函式

建立一個已完成且帶有指定例外的任務。

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 用於完成任務的例外。 |

### 返回值

已失敗的任務。

## System::Threading::Tasks::FromException(const Exception\&) 函式

建立一個已完成且帶有指定例外與結果類型的任務。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TResult | 任務結果的類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 用於完成任務的例外。 |

### 返回值

已失敗且結果類型為指定值的任務。

## 另見

* 型別別名 [TaskPtr](../../system/taskptr/)
* 型別別名 [Exception](../../system/exception/)
* 型別別名 [RTaskPtr](../../system/rtaskptr/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)