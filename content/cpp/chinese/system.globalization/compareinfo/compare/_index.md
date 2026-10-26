---
title: Compare()
second_title: Aspose.Slides C++ API 参考
description: 比较字符串。未实现。
type: docs
weight: 66
url: /zh/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const 方法

比较字符串。未实现。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 左侧字符串。 |
| string2 | const [String](../../../system/string/)\& | 右侧字符串。 |

### 返回值

如果左侧字符串在右侧字符串之前返回负值，如果相等返回零，否则返回正值。

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const 方法

比较字符串。仅支持 Ordinal 和 OrdinalIgnoreCase 模式。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | 左侧字符串。 |
| b | const [String](../../../system/string/)\& | 右侧字符串。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比较类型。 |

### 返回值

如果左侧字符串在右侧字符串之前返回负值，如果相等返回零，否则返回正值。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const 方法

比较一个字符串的一段与第二个字符串的一段。未实现。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一个字符串。 |
| offset1 | int | **string1** 中字符的起始索引。 |
| length1 | int | 要比较的 **string1** 中的字符数。 |
| string2 | const [String](../../../system/string/)\& | 第二个字符串。 |
| offset2 | int | **string2** 中字符的起始索引。 |
| length2 | int | 要比较的 **string2** 中的字符数。 |

### 返回值

如果第一个字符串段在第二个字符串段之前返回负值，如果相等返回零，否则返回正值。

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const 方法

使用字符串比较方法比较一个字符串的结束段与第二个字符串的结束段。未实现。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一个字符串。 |
| offset1 | int | **string1** 中字符的起始索引。 |
| string2 | const [String](../../../system/string/)\& | 第二个字符串。 |
| offset2 | int | **string2** 中字符的起始索引。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比较选项。 |

### 返回值

如果第一个字符串段在第二个字符串段之前返回负值，如果相等返回零，否则返回正值。

## CompareInfo::Compare(const String\&, int, const String\&, int) const 方法

比较一个字符串的结束段与第二个字符串的结束段。未实现。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一个字符串。 |
| offset1 | int | **string1** 中字符的起始索引。 |
| string2 | const [String](../../../system/string/)\& | 第二个字符串。 |
| offset2 | int | **string2** 中字符的起始索引。 |

### 返回值

如果第一个字符串段在第二个字符串段之前返回负值，如果相等返回零，否则返回正值。

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const 方法

使用字符串比较方法比较一个字符串的一段与第二个字符串的一段。未实现。

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 第一个字符串。 |
| offset1 | int | **string1** 中字符的起始索引。 |
| length1 | int | 要比较的 **string1** 中的字符数。 |
| string2 | const [String](../../../system/string/)\& | 第二个字符串。 |
| offset2 | int | **string2** 中字符的起始索引。 |
| length2 | int | 要比较的 **string2** 中的字符数。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比较选项。 |

### 返回值

如果第一个字符串段在第二个字符串段之前返回负值，如果相等返回零，否则返回正值。

## 另见

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)