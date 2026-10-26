---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API 参考
description: 获取与指定字符关联的数值。
type: docs
weight: 27
url: /zh/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) method


获取与指定字符关联的数值。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char16_t | Unicode 字符。 |

### 返回值

数值，若指定字符不是数字字符则返回 -1。

## CharUnicodeInfo::GetNumericValue(const String\&, int) method


获取字符串中指定索引处字符的数值。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字符的字符串。 |
| index | int | Unicode 字符的索引。 |

### 返回值

数值，若指定字符不是数字字符则返回 -1。

## 参见

* 类 [CharUnicodeInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)