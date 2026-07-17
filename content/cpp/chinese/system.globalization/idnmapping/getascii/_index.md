---
title: GetAscii()
second_title: Aspose.Slides C++ API 参考
description: 将 Unicode 域名转换为 ASCII 等价字符串。
type: docs
weight: 79
url: /zh/system.globalization/idnmapping/getascii/
---
## IdnMapping::GetAscii(const String\&) const method

[Convert](../../../system/convert/) unicode 域名转换为 ascii 等价字符串。

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于转换。 |

### 返回值

Ascii 等价的 unicode 字符串。

## IdnMapping::GetAscii(const String\&, int) const method

[Convert](../../../system/convert/) unicode 域名转换为 ascii 等价字符串。

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode, int index) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于转换。 |
| index | int | 要转换的子字符串的起始索引。 |

### 返回值

Ascii 等价的 unicode 字符串。

## IdnMapping::GetAscii(const String\&, int, int) const method

[Convert](../../../system/convert/) unicode 域名转换为 ascii 等价字符串。

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode, int index, int count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于转换。 |
| index | int | 要转换的子字符串的起始索引。 |
| count | int | 要转换的字符数。 |

### 返回值

Ascii 等价的 unicode 字符串。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IdnMapping](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)