---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的字串轉換為 bool 類型的值。
type: docs
weight: 14
url: /zh-hant/system/boolean/tryparse/
---
## Boolean::TryParse(const String\&, bool\&) 方法

將指定的字串轉換為 bool 類型的值。

```cpp
static bool System::Boolean::TryParse(const String &value, bool &result)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **bool**\& | 指向 bool 變數的參考，用於放置轉換結果；如果指定的字串等於 "True" 則結果為 true，若等於 "False" 則結果為 false。 |

### 傳回值

如果指定的字串等於 "True" 或 "False" 則為 true，否則為 false。

## 另見

* 類別 [String](../../string/)
* 類別 [Boolean](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)