---
title: GetUnicode()
second_title: Aspose.Slides for C++ API 参考
description: 将 ASCII 域名转换为 Unicode 等价形式。
type: docs
weight: 92
url: /zh/system.globalization/idnmapping/getunicode/
---
## IdnMapping::GetUnicode(const String\&) const 方法


[Convert](../../../system/convert/) ASCII 域名转换为 Unicode 等价形式。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii) const
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 进行转换。 |

### 返回值

Unicode 等价的 ASCII 字符串。

## IdnMapping::GetUnicode(const String\&, int) const 方法


[Convert](../../../system/convert/) ASCII 域名转换为 Unicode 等价形式。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index) const
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 进行转换。 |
| index | int | 要转换的子字符串的起始索引 |

### 返回值

Unicode 等价的 ASCII 字符串。

## IdnMapping::GetUnicode(const String\&, int, int) const 方法


[Convert](../../../system/convert/) ASCII 域名转换为 Unicode 等价形式。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index, int count) const
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 进行转换。 |
| index | int | 要转换的子字符串的起始索引 |
| count | int | 要转换的字符数。 |

### 返回值

Unicode 等价的 ASCII 字符串。

## 另见

* 类 [String](../../../system/string/)
* 类 [IdnMapping](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)