---
title: Print()
second_title: Aspose.Slides for C++ API 參考文件
description: 將訊息輸出至除錯介面。
type: docs
weight: 79
url: /zh-hant/system.diagnostics/debug/print/
---
## Debug::Print(const String\&) 方法

將訊息輸出到除錯介面。

```cpp
static void System::Diagnostics::Debug::Print(const String &message)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 要寫入的訊息。 |

## Debug::Print(const String\&, const System::ArrayPtr\<SharedPtr\<System::Object\>\>\&) 方法

將訊息輸出到除錯介面。

```cpp
static void System::Diagnostics::Debug::Print(const String &format, const System::ArrayPtr<SharedPtr<System::Object>> &args)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 格式字串。 |
| args | const [System::ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\>\& | 用於取代格式字串的參數。 |

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 結構 [Debug](../)
* 命名空間 [System::Diagnostics](../../)
* 函式庫 [Aspose.Slides](../../../)