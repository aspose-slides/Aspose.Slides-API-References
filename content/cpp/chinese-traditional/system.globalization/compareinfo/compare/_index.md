---
title: Compare()
second_title: Aspose.Slides for C++ API 參考
description: 比較字串。未實作。
type: docs
weight: 66
url: /zh-hant/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method


比較字串。未實作。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 左側字串 (LHS)。 |
| string2 | const [String](../../../system/string/)\& | 右側字串 (RHS)。 |

### 返回值

負值表示左側字串 (LHS) 在右側字串 (RHS) 之前，零表示相等，正值表示左側字串在右側字串之後。

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method


比較字串。僅支援 Ordinal 與 OrdinalIgnoreCase 模式。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | 左側字串 (LHS)。 |
| b | const [String](../../../system/string/)\& | 右側字串 (RHS)。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較類型。 |

### 返回值

負值表示左側字串 (LHS) 在右側字串 (RHS) 之前，零表示相等，正值表示左側字串在右側字串之後。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method


比較一個字串的部分與另一個字串的部分。未實作。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一個字串。 |
| offset1 | int | **string1** 中字元的起始索引。 |
| length1 | int | 要比較的 **string1** 中字元數量。 |
| string2 | const [String](../../../system/string/)\& | 第二個字串。 |
| offset2 | int | **string2** 中字元的起始索引。 |
| length2 | int | 要比較的 **string2** 中字元數量。 |

### 返回值

負值表示第一個字串區段在第二個字串區段之前，零表示相等，正值表示第一個字串區段在第二個字串區段之後。

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method


比較一個字串的結尾區段與另一個字串的結尾區段，使用字串比較方法。未實作。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一個字串。 |
| offset1 | int | **string1** 中字元的起始索引。 |
| string2 | const [String](../../../system/string/)\& | 第二個字串。 |
| offset2 | int | **string2** 中字元的起始索引。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較選項。 |

### 返回值

負值表示第一個字串區段在第二個字串區段之前，零表示相等，正值表示第一個字串區段在第二個字串區段之後。

## CompareInfo::Compare(const String\&, int, const String\&, int) const method


比較一個字串的結尾區段與另一個字串的結尾區段。未實作。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一個字串。 |
| offset1 | int | **string1** 中字元的起始索引。 |
| string2 | const [String](../../../system/string/)\& | 第二個字串。 |
| offset2 | int | **string2** 中字元的起始索引。 |

### 返回值

負值表示第一個字串區段在第二個字串區段之前，零表示相等，正值表示第一個字串區段在第二個字串區段之後。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method


比較一個字串的部分與另一個字串的部分，使用字串比較方法。未實作。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一個字串。 |
| offset1 | int | **string1** 中字元的起始索引。 |
| length1 | int | 要比較的 **string1** 中字元數量。 |
| string2 | const [String](../../../system/string/)\& | 第二個字串。 |
| offset2 | int | **string2** 中字元的起始索引。 |
| length2 | int | 要比較的 **string2** 中字元數量。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較選項。 |

### 返回值

負值表示第一個字串區段在第二個字串區段之前，零表示相等，正值表示第一個字串區段在第二個字串區段之後。

## 另見

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)