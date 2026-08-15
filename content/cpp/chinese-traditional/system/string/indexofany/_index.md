---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API 參考
description: 字符向前查找。
type: docs
weight: 638
url: /zh-hant/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const 方法

字元向前查找。

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要查找的字元。 |
| startIndex | int | [Index](../../index/) 以開始查找。 |

### 返回值

[Index](../../index/) 首個字符位置（自 startIndex 起）或 -1（未找到）。

## String::IndexOfAny(const String\&, int) const 方法

依次在此字串中搜尋 str 的所有字符。若找到第一個字符，返回其位置；否則繼續搜尋第二個字符，依此類推。

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 要查找的字符。字符的順序很重要。 |
| startIndex | int | 開始查找的位置。 |

### 返回值

[Index](../../index/) 首個找到的字符，若未找到則為 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const 方法

在整個字串中搜尋任何傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，然後比較第二個字符，依此類推。返回第一個匹配目標字符的索引。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符。順序不重要。 |

### 返回值

[Index](../../index/) 第一個匹配的字符，若未找到則為 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 方法

在子字串中搜尋任何傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，然後比較第二個字符，依此類推。返回第一個匹配目標字符的索引。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符。順序不重要。 |
| startindex | **int32_t** | [Index](../../index/) 開始查找的位置。 |

### 返回值

[Index](../../index/) 第一個匹配的字符，若未找到則為 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 方法

在子字串中搜尋任何傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，然後比較第二個字符，依此類推。返回第一個匹配目標字符的索引。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符。順序不重要。 |
| startindex | **int32_t** | [Index](../../index/) 開始查找的位置。 |
| count | **int32_t** | 要查詢的字符數量。 |

### 返回值

[Index](../../index/) 第一個匹配的字符，若未找到則為 -1。

## 另見

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)