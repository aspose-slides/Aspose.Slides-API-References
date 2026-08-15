---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 UTF-16 代理對轉換為 UTF-32 代碼單元。
type: docs
weight: 287
url: /zh-hant/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) 方法

將指定的 UTF-16 代理對轉換為 UTF-32 代碼單元。

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| highSurrogate | char_t | 要轉換的 UTF-16 代理對的高位代理 |
| lowSurrogate | char_t | 要轉換的 UTF-16 代理對的低位代理 |

### 返回值

由轉換產生的 UTF-32 代碼單元

## Char::ConvertToUtf32(const String\&, int) 方法

將字串中指定位置的 UTF-16 編碼字元或代理對的值轉換為 UTF-32 代碼單元。

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 包含字元或代理對的字串 |
| index | int | 指定字串中字元或代理對的索引位置 |

### 返回值

由轉換產生的 UTF-32 代碼單元

## 另請參閱

* 類別 [Char](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)