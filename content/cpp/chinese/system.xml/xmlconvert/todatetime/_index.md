---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 参考
description: 将 String 转换为 DateTime 等价项。
type: docs
weight: 417
url: /zh/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) 方法

将 [String](../../../system/string/) 转换为 [DateTime](../../../system/datetime/) 等价项。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。 |

### 返回值

字符串的 [DateTime](../../../system/datetime/) 等价项。

## XmlConvert::ToDateTime(const String\&, const String\&) 方法

将 [String](../../../system/string/) 转换为 [DateTime](../../../system/datetime/) 等价项。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。 |
| format | const [String](../../../system/string/)\& | 要应用于已转换 [DateTime](../../../system/datetime/) 的格式结构。有效格式包括 “yyyy-MM-ddTHH:mm:sszzzzzz” 及其子集。字符串将根据此格式进行验证。 |

### 返回值

字符串的 [DateTime](../../../system/datetime/) 等价项。

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) 方法

将 [String](../../../system/string/) 转换为 [DateTime](../../../system/datetime/) 等价项。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的字符串。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 包含要应用于已转换 [DateTime](../../../system/datetime/) 的格式结构的数组。有效格式包括 “yyyy-MM-ddTHH:mm:sszzzzzz” 及其子集。 |

### 返回值

字符串的 [DateTime](../../../system/datetime/) 等价项。

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) 方法

使用指定的 XmlDateTimeSerializationMode 将 [String](../../../system/string/) 转换为 [DateTime](../../../system/datetime/)。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要转换的 [String](../../../system/string/) 值。 |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | 指定日期应转换为本地时间还是保持为协调世界时（UTC）的枚举值之一（如果是 UTC 日期）。 |

### 返回值

[String](../../../system/string/) 的 [DateTime](../../../system/datetime/) 等价项。

## 另见

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)