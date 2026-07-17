---
title: ToDateTimeOffset()
second_title: Aspose.Slides for C++ API 参考
description: 将提供的 String 转换为等价的 DateTimeOffset。
type: docs
weight: 430
url: /zh/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) 方法


将提供的 [String](../../../system/string/) 转换为等价的 [DateTimeOffset](../../../system/datetimeoffset/)。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。该字符串必须符合 W3C 推荐的 XML dateTime 类型的子集。更多信息请参阅 XML [Schema](../../../system.xml.schema/) 规范的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 部分。 |

### 返回值

提供的字符串的 [DateTimeOffset](../../../system/datetimeoffset/) 等价值。

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) 方法


将提供的 [String](../../../system/string/) 转换为等价的 [DateTimeOffset](../../../system/datetimeoffset/)。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。 |
| format | const [String](../../../system/string/)\& | 用于转换 **s** 的格式。format 参数可以是 W3C 推荐的 XML dateTime 类型的任意子集。更多信息请参阅 XML [Schema](../../../system.xml.schema/) 规范的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 部分。字符串 **s** 将依据此格式进行验证。 |

### 返回值

提供的字符串的 [DateTimeOffset](../../../system/datetimeoffset/) 等价值。

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) 方法


将提供的 [String](../../../system/string/) 转换为等价的 [DateTimeOffset](../../../system/datetimeoffset/)。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 一个格式数组，可用于转换 **s**。**formats** 中的每个格式可以是 W3C 推荐的 XML dateTime 类型的任意子集。更多信息请参阅 XML [Schema](../../../system.xml.schema/) 规范的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 部分。字符串 **s** 将针对这些格式中的一种进行验证。 |

### 返回值

提供的字符串的 [DateTimeOffset](../../../system/datetimeoffset/) 等价值。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [DateTimeOffset](../../../system/datetimeoffset/)
* 类 [String](../../../system/string/)
* 类 [XmlConvert](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)