---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 子字串向後搜尋。
type: docs
weight: 651
url: /zh-hant/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method

向後搜尋子字串。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要搜尋的子字串。 |
| startIndex | int | 來源字串中開始搜尋的位置。 |

### 傳回值

[Index](../../index/) 為最後找到的子字串位置，若未找到則為 -1。若搜尋字串為空，總是回傳字串長度。

## String::LastIndexOf(const String\&, System::StringComparison) const method

向後搜尋子字串。

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要搜尋的子字串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 傳回值

[Index](../../index/) 為最後找到的子字串位置，若未找到則為 -1。若搜尋字串為空，總是回傳字串長度。

## String::LastIndexOf(const String\&, int, System::StringComparison) const method

向後搜尋子字串。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要搜尋的子字串。 |
| startIndex | int | 來源字串中開始搜尋的位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 傳回值

[Index](../../index/) 為最後找到的子字串位置，若未找到則為 -1。若搜尋字串為空，總是回傳字串長度。

## String::LastIndexOf(const String\&, int, int, StringComparison) const method

向後搜尋子字串。

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 要搜尋的子字串。 |
| startIndex | int | 來源字串中開始搜尋的位置。 |
| count | int | 要搜尋的字元數量。 |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 傳回值

[Index](../../index/) 為最後找到的子字串位置，若未找到則為 -1。若搜尋字串為空，總是回傳 startIndex+count。

## String::LastIndexOf(char_t) const method

向後搜尋字元。

```cpp
int System::String::LastIndexOf(char_t value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要搜尋的字元。 |

### 傳回值

[Index](../../index/) 為最後的字元位置，若未找到則為 -1。

## String::LastIndexOf(char_t, int32_t) const method

向後搜尋字元。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要搜尋的字元。 |
| startIndex | **int32_t** | [Index](../../index/) 為開始搜尋的位置。 |

### 傳回值

[Index](../../index/) 為從 startIndex 起最後的字元位置，若未找到則為 -1。

## String::LastIndexOf(char_t, int32_t, int32_t) const method

向後搜尋字元。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要搜尋的字元。 |
| startIndex | **int32_t** | [Index](../../index/) 為開始搜尋的位置。 |
| count | **int32_t** | 要搜尋的字元數量。 |

### 傳回值

[Index](../../index/) 為從 startIndex 起最後的字元位置，若未找到則為 -1。

## 參見

* 列舉 [StringComparison](../../stringcomparison/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)