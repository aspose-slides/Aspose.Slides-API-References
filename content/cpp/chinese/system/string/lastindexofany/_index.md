---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API 参考
description: 在整个字符串中向后搜索传入的任意字符。将字符串的最后一个字符与 anyOf 中的所有字符进行比较，然后比较前一个字符，依此类推。返回找到的第一个匹配项的索引。
type: docs
weight: 664
url: /zh/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const 方法

在整个字符串中向后搜索传入的任意字符。将字符串的最后一个字符与 anyOf 中的所有字符进行比较，然后比较前一个字符，依此类推。返回找到的第一个匹配项的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。顺序无关紧要。 |

### 返回值

最后匹配字符的索引，如果未找到则为 -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 方法

在子字符串中向后搜索传入的任意字符。将字符串的最后一个字符与 anyOf 中的所有字符进行比较，然后比较前一个字符，依此类推。返回找到的第一个匹配项的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。顺序无关紧要。 |
| startindex | **int32_t** | 开始查找的索引。 |

### 返回值

最后匹配字符的索引，如果未找到则为 -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 方法

在子字符串中向后搜索传入的任意字符。将字符串的最后一个字符与 anyOf 中的所有字符进行比较，然后比较前一个字符，依此类推。返回找到的第一个匹配项的索引。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要查找的字符集合。顺序无关紧要。 |
| startindex | **int32_t** | 开始查找的索引。 |
| count | **int32_t** | 要遍历的字符数量。 |

### 返回值

最后匹配字符的索引，如果未找到则为 -1。

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)