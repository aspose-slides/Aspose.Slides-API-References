---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API 参考
description: 使用序数模式对两个字符串进行小于、等于、大于比较。
type: docs
weight: 833
url: /zh/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) 方法

使用序数模式对两个字符串进行小于、等于、大于比较。

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比较的第一个字符串。 |
| strB | const [String](../)\& | 要比较的第二个字符串。 |

### 返回值

如果第一个子串小于第二个子串则返回负值；如果相等则返回零；否则返回正值。

## String::CompareOrdinal(const String\&, int, const String\&, int, int) 方法

使用序数模式对两个字符串进行小于、等于、大于比较。

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 要比较的第一个字符串。 |
| indexA | int | 第一个字符串子串的起始索引。 |
| strB | const [String](../)\& | 要比较的第二个字符串。 |
| indexB | int | 第二个字符串子串的起始索引。 |
| length | int | 要比较的字符数量。 |

### 返回值

如果第一个子串小于第二个子串则返回负值；如果相等则返回零；否则返回正值。

## 另请参见

* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)