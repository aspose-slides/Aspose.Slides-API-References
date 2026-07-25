---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 部分文字列の後方検索。
type: docs
weight: 651
url: /ja/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const メソッド


部分文字列の後方検索。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | 検索対象の部分文字列。 |
| startIndex | int | 検索を開始する元文字列内の位置。 |

### 戻り値

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, System::StringComparison) const メソッド


部分文字列の後方検索。

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | 検索対象の部分文字列。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### 戻り値

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, int, System::StringComparison) const メソッド


部分文字列の後方検索。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | 検索対象の部分文字列。 |
| startIndex | int | 検索を開始する元文字列内の位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### 戻り値

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, int, int, StringComparison) const メソッド


部分文字列の後方検索。

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索対象の部分文字列。 |
| startIndex | int | 検索を開始する元文字列内の位置。 |
| count | int | 検索対象の文字数。 |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### 戻り値

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## String::LastIndexOf(char_t) const メソッド


文字の後方検索。

```cpp
int System::String::LastIndexOf(char_t value) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 検索対象の文字。 |

### 戻り値

[Index](../../index/) of last character position or -1 if not found.

## String::LastIndexOf(char_t, int32_t) const メソッド


文字の後方検索。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 検索対象の文字。 |
| startIndex | **int32_t** | [Index](../../index/) to start lookup at. |

### 戻り値

[Index](../../index/) of last character position since startIndex or -1 if not found.

## String::LastIndexOf(char_t, int32_t, int32_t) const メソッド


文字の後方検索。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 検索対象の文字。 |
| startIndex | **int32_t** | [Index](../../index/) to start lookup at. |
| count | **int32_t** | Number of characters to look through |

### 戻り値

[Index](../../index/) of last character position since startIndex or -1 if not found.

## 関連項目

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)