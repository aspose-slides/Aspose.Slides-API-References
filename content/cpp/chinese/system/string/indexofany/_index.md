---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API 参考
description: 字符向前查找。
type: docs
weight: 638
url: /zh/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const 方法

字符向前查找。

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要查找的字符。 |
| startIndex | int | 开始查找的索引。 |

### 返回值

自 startIndex 起的第一个字符位置索引，未找到则返回 -1。

## String::IndexOfAny(const String\&, int) const 方法

因此在此字符串中查找 str 的所有字符。如果找到第一个字符，则返回其位置；否则继续查找第二个字符，依此类推。

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 要查找的字符集合。字符顺序重要。 |
| startIndex | int | 开始查找的索引。 |

### 返回值

找到的第一个字符的位置索引，未找到则返回 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const 方法

在整个字符串中查找传入的任意字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的字符位置。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。字符顺序无关紧要。 |

### 返回值

第一个匹配字符的索引，未找到则返回 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 方法

在子串中查找传入的任意字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的字符位置。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。字符顺序无关紧要。 |
| startindex | **int32_t** | 开始查找的索引。 |

### 返回值

第一个匹配字符的索引，未找到则返回 -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 方法

在子串中查找传入的任意字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的字符位置。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。字符顺序无关紧要。 |
| startindex | **int32_t** | 开始查找的索引。 |
| count | **int32_t** | 要遍历的字符数量。 |

### 返回值

第一个匹配字符的索引，未找到则返回 -1。

## 另请参阅

* 类型别名 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)