---
title: ToDateTimeOffset()
second_title: Aspose.Slides for C++ API Reference
description: Converts the supplied String to a DateTimeOffset equivalent.
type: docs
weight: 430
url: /cpp/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const [String](../../../system/string/)\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | The string to convert. The string must conform to a subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. |

### Return Value

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlConvert::ToDateTimeOffset(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | The string to convert. |
| format | const [String](../../../system/string/)\& | The format from which **s** is converted. The format parameter can be any subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. The string **s** is validated against this format. |

### Return Value

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlConvert::ToDateTimeOffset(const [String](../../../system/string/)\&, const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | The string to convert. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | An array of formats from which **s** can be converted. Each format in **formats** can be any subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. The string **s** is validated against one of these formats. |

### Return Value

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
