---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得與指定字元相關聯的數值。
type: docs
weight: 27
url: /zh-hant/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) 方法


取得與指定字元相關聯的數值。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char16_t | Unicode 字元。 |

### 返回值

若指定的字元不是數值字元，則返回數值或 -1。

## CharUnicodeInfo::GetNumericValue(const String\&, int) 方法


取得與字串中指定索引之字元相關聯的數值。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字元的字串。 |
| index | int | Unicode 字元的索引。 |

### 返回值

若指定的字元不是數值字元，則返回數值或 -1。

## 另請參考

* 類別 [CharUnicodeInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Globalization](../../)
* 程式庫 [Aspose.Slides](../../../)