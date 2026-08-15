---
title: FromResult()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個已成功完成且具有指定結果的任務。
type: docs
weight: 144
url: /zh-hant/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) 函式

建立一個已成功完成且具有指定結果的任務。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 任務結果的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| result | TResult | 完成任務時使用的結果值。 |

### 返回值

已成功完成的任務。

## 參見

* 型別定義 [RTaskPtr](../../system/rtaskptr/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)