---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 子字串向前搜尋。
type: docs
weight: 625
url: /zh-hant/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const 方法

子字串向前搜尋。

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

[Index](../../index/) 代表第一個找到的子字串，若未找到則返回 -1。若搜尋字串為空，始終返回 0。

## String::IndexOf(char_t, int) const 方法

字元向前搜尋。

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要查找的字元。 |
| startIndex | int | [Index](../../index/) 以開始搜尋。 |

### 返回值

[Index](../../index/) 代表自 startIndex 起的第一個字元位置，若未找到則返回 -1。

## String::IndexOf(char_t, int, int) const 方法

子字串中的字元向前搜尋。

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要查找的字元。 |
| startIndex | int | [Index](../../index/) 以開始搜尋。 |
| count | int | 要檢視的字元數。 |

### 返回值

[Index](../../index/) 代表自 startIndex 起的第一個字元位置，若未找到則返回 -1。

## String::IndexOf(const String\&, int) const 方法

子字串向前搜尋。

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字串。 |
| startIndex | int | 在來源字串中開始搜尋的位置。 |

### 返回值

[Index](../../index/) 代表第一個找到的子字串，若未找到則返回 -1。若搜尋字串為空，始終返回 startIndex。

## String::IndexOf(const String\&, int, System::StringComparison) const 方法

子字串向前搜尋。

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字串。 |
| startIndex | int | 在來源字串中開始搜尋的位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

[Index](../../index/) 代表第一個找到的子字串，若未找到則返回 -1。若搜尋字串為空，始終返回 startIndex。

## String::IndexOf(const String\&, int, int, System::StringComparison) const 方法

子字串向前搜尋。

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的子字串。 |
| startIndex | int | 在來源字串中開始搜尋的位置。 |
| count | int | 要檢視的字元數。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

[Index](../../index/) 代表第一個找到的子字串，若未找到則返回 -1。若搜尋字串為空，始終返回 startIndex。

## String::IndexOf(const String\&, int, int) const 方法

子字串向前搜尋。

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字串。 |
| startIndex | int | 在來源字串中開始搜尋的位置。 |
| count | int | 要檢視的字元數。 |

### 返回值

[Index](../../index/) 代表第一個找到的子字串，若未找到則返回 -1。若搜尋字串為空，始終返回 startIndex。

## 另請參閱

* 列舉 [StringComparison](../../stringcomparison/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)