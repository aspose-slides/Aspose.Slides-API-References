---
title: IndexOf()
second_title: Aspose.Slides C++ API 参考
description: 子字符串向前查找。
type: docs
weight: 625
url: /zh/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const 方法

子字符串向前查找。

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字符串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回首次找到的子字符串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 0。

## String::IndexOf(char_t, int) const 方法

字符向前查找。

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要查找的字符。 |
| startIndex | int | 查找开始的索引。 |

### 返回值

返回自 startIndex 起的首个字符位置的索引，如果未找到则返回 -1。

## String::IndexOf(char_t, int, int) const 方法

子字符串中的字符向前查找。

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要查找的字符。 |
| startIndex | int | 查找开始的索引。 |
| count | int | 要遍历的字符数。 |

### 返回值

返回自 startIndex 起的首个字符位置的索引，如果未找到则返回 -1。

## String::IndexOf(const String\&, int) const 方法

子字符串向前查找。

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字符串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |

### 返回值

返回首次找到的子字符串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 startIndex。

## String::IndexOf(const String\&, int, System::StringComparison) const 方法

子字符串向前查找。

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字符串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回首次找到的子字符串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 startIndex。

## String::IndexOf(const String\&, int, int, System::StringComparison) const 方法

子字符串向前查找。

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../)\& | 要查找的子字符串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |
| count | int | 要遍历的字符数。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

返回首次找到的子字符串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 startIndex。

## String::IndexOf(const String\&, int, int) const 方法

子字符串向前查找。

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | 要查找的子字符串。 |
| startIndex | int | 在源字符串中开始查找的位置。 |
| count | int | 要遍历的字符数。 |

### 返回值

返回首次找到的子字符串的索引，如果未找到则返回 -1。对于空的查找字符串，总是返回 startIndex。

## 另请参阅

* 枚举 [StringComparison](../../stringcomparison/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)