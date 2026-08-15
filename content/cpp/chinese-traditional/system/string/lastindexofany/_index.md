---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API 參考
description: 向後搜尋整個字串中傳入的任意字元。將字串最後一個字元與 anyOf 中的所有字元比較，然後比較前一個字元，依此類推。返回首次匹配的索引。
type: docs
weight: 664
url: /zh-hant/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const 方法

向後搜尋整個字串中任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，然後比較前一個字符，依此類推。返回首次匹配的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要搜尋的字符集合。順序不影響。 |

### 回傳值

[Index](../../index/) 為最後匹配字符的索引，若未找到則返回 -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 方法

向後搜尋子字串中任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，然後比較前一個字符，依此類推。返回首次匹配的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要搜尋的字符集合。順序不影響。 |
| startindex | **int32_t** | [Index](../../index/) 用於指定開始查找的索引。 |

### 回傳值

[Index](../../index/) 為最後匹配字符的索引，若未找到則返回 -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 方法

向後搜尋子字串中任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，然後比較前一個字符，依此類推。返回首次匹配的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要搜尋的字符集合。順序不影響。 |
| startindex | **int32_t** | [Index](../../index/) 用於指定開始查找的索引。 |
| count | **int32_t** | 要搜尋的字符數量。 |

### 回傳值

[Index](../../index/) 為最後匹配字符的索引，若未找到則返回 -1。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)