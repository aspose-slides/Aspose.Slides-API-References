---
title: Compare()
second_title: Aspose.Slides for C++ API 参考
description: 比较两个子字符串的大小（小于、等于、大于）。
type: docs
weight: 820
url: /zh/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) 方法

比较两个子字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| indexA | int | 第一个字符串子串的起始位置。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| indexB | int | 第二个字符串子串的起始位置。 |
| length | int | 要比较的字符数。 |
| ignoreCase | **bool** | 指定比较是否不区分大小写。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 方法

比较两个子字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| indexA | int | 第一个字符串子串的起始位置。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| indexB | int | 第二个字符串子串的起始位置。 |
| length | int | 要比较的字符数。 |
| ignoreCase | **bool** | 指定比较是否不区分大小写。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 用于比较的区域性。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## String::Compare(const String\&, const String\&, System::StringComparison) 方法

比较两个字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) 方法

比较两个字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| indexA | int | 第一个字符串子串的起始位置。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| indexB | int | 第二个字符串子串的起始位置。 |
| length | int | 要比较的字符数。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 模式。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## String::Compare(const String\&, const String\&, bool) 方法

比较两个字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| ignoreCase | **bool** | 指定比较是否不区分大小写。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 方法

比较两个字符串的大小（小于、等于、大于）。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| strA | const [String](../)\& | 第一个待比较的字符串。 |
| strB | const [String](../)\& | 第二个待比较的字符串。 |
| ignoreCase | **bool** | 指定比较是否不区分大小写。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 用于比较的区域性。 |

### 返回值

如果第一个子字符串小于第二个，则返回负值；如果相等，则返回零；否则返回正值。

## 参见

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)