---
title: GetDigitValue()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定字符的数字值。
type: docs
weight: 14
url: /zh/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) 方法

获取指定字符的数字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char16_t | Unicode字符。 |

### 返回值

数字值，若指定字符不是数字则返回-1。

## CharUnicodeInfo::GetDigitValue(const String\&, int) 方法

获取字符串中指定索引处字符的数字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字符的字符串。 |
| index | int | Unicode 字符的索引。 |

### 返回值

数字值，若指定字符不是数字则返回-1。

## 另请参阅

* 类 [CharUnicodeInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)