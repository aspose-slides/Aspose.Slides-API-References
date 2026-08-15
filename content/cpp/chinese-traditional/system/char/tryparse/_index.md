---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將僅包含單一字元的字串轉換為 UTF-16 字元。僅當輸入字串不為 null 且長度恰好為一個字元時，函式才會成功。
type: docs
weight: 300
url: /zh-hant/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) method

嘗試將僅包含單一字元的字串轉換為 UTF-16 字元。僅當輸入字串不為 null 且長度恰好為一個字元時，函式才會成功。

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) 以轉換 |
| result | char_t\& | 若轉換成功，將包含轉換結果的輸出變數 |

### 傳回值

True 若轉換成功，否則 - false

## 另見

* 類別 [String](../../string/)
* 類別 [Char](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)