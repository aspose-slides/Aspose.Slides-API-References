---
title: GetDecimalDigitValue()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定字符的十进制数字值。
type: docs
weight: 1
url: /zh/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) 方法

获取指定字符的十进制数字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char16_t | Unicode 字符。 |

### 返回值

十进制数字值；如果指定的字符不是十进制数字，则返回 -1。

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) 方法

获取字符串中指定索引处字符的十进制数字值。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字符的字符串。 |
| index | int | Unicode 字符的索引。 |

### 返回值

十进制数字值；如果指定的字符不是十进制数字，则返回 -1。

## 另见

* 类 [CharUnicodeInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)