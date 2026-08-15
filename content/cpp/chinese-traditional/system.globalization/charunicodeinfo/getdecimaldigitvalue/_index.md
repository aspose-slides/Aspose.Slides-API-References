---
title: GetDecimalDigitValue()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定字元的十進位數字值。
type: docs
weight: 1
url: /zh-hant/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) 方法

取得指定字元的十進位數字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char16_t | Unicode 字元。 |

### 傳回值

十進位數字值，若指定字元不是十進位數字則回傳 -1。

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) 方法

取得字串中指定索引之字元的十進位數字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字元的字串。 |
| index | int | Unicode 字元的索引。 |

### 傳回值

十進位數字值，若指定字元不是十進位數字則回傳 -1。

## 另請參閱

* 類別 [CharUnicodeInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)