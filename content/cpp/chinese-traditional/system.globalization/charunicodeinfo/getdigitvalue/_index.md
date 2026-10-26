---
title: GetDigitValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定字元的數位值。
type: docs
weight: 14
url: /zh-hant/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) 方法

取得指定字元的數位值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char16_t | Unicode 字元。 |

### 回傳值

數位值；如果指定的字元不是數字，則返回 -1。

## CharUnicodeInfo::GetDigitValue(const String\&, int) 方法

取得字串中指定索引之字元的數位值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字元的字串。 |
| index | int | Unicode 字元的索引。 |

### 回傳值

數位值；如果指定的字元不是數字，則返回 -1。

## 另請參閱

* 類別 [CharUnicodeInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)