---
title: GetUnicodeCategory()
second_title: Aspose.Slides for C++ API 参考
description: 获取字符的 Unicode 类别。
type: docs
weight: 40
url: /zh/system.globalization/charunicodeinfo/getunicodecategory/
---
## CharUnicodeInfo::GetUnicodeCategory(char16_t) 方法

获取字符的 Unicode 类别。

```cpp
static UnicodeCategory System::Globalization::CharUnicodeInfo::GetUnicodeCategory(char16_t ch)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char16_t | Unicode 字符。 |

### 返回值

Unicode 类别。

## CharUnicodeInfo::GetUnicodeCategory(const String\&, int) 方法

获取字符串中指定索引处字符的 Unicode 类别。

```cpp
static UnicodeCategory System::Globalization::CharUnicodeInfo::GetUnicodeCategory(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 包含 Unicode 字符的字符串。 |
| index | int | Unicode 字符的索引。 |

### 返回值

Unicode 类别。

## 参见

* Enum [UnicodeCategory](../../unicodecategory/)
* 类 [CharUnicodeInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)