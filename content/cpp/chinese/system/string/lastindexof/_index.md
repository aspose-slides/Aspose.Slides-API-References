---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 参考
description: 子串向后查找。
type: docs
weight: 651
url: /zh/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const 方法

子串向后查找。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |

### 返回值

返回最后找到的子串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回字符串长度。

## String::LastIndexOf(const String\&, System::StringComparison) const 方法

子串向后查找。

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回最后找到的子串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回字符串长度。

## String::LastIndexOf(const String\&, int, System::StringComparison) const 方法

子串向后查找。

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回最后找到的子串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回字符串长度。

## String::LastIndexOf(const String\&, int, int, StringComparison) const 方法

子串向后查找。

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的子串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |
| count | int | 要查找的字符数。 |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回最后找到的子串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 startIndex+count。

## String::LastIndexOf(char_t) const 方法

字符向后查找。

```cpp
int System::String::LastIndexOf(char_t value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要查找的字符。 |

### 返回值

返回最后一个字符的位置索引，如果未找到则返回 -1。

## String::LastIndexOf(char_t, int32_t) const 方法

字符向后查找。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要查找的字符。 |
| startIndex | **int32_t** | 开始查找的索引。 |

### 返回值

返回自 startIndex 起的最后一个字符的位置索引，如果未找到则返回 -1。

## String::LastIndexOf(char_t, int32_t, int32_t) const 方法

字符向后查找。

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要查找的字符。 |
| startIndex | **int32_t** | 开始查找的索引。 |
| count | **int32_t** | 要查找的字符数 |

### 返回值

返回自 startIndex 起的最后一个字符的位置索引，如果未找到则返回 -1。

## 另请参见

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)