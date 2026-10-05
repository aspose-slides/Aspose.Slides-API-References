---
title: ToDateTime()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a DateTime equivalent.
type: docs
weight: 417
url: /system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

A [DateTime](../../../system/datetime/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is an empty string or is not in the correct format. |


## XmlConvert::ToDateTime(const String&, const String&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |
| format | const [String](../../../system/string/)& | The format structure to apply to the converted [DateTime](../../../system/datetime/). Valid formats include "yyyy-MM-ddTHH:mm:sszzzzzz" and its subsets. The string is validated against this format. |

### Return Value

A [DateTime](../../../system/datetime/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** or **format** is [String::Empty](../../../system/string/empty/) or **s** does not contain a date and time that corresponds to **format**. |


## XmlConvert::ToDateTime(const String&, const ArrayPtr\<String\>&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>& | An array containing the format structures to apply to the converted [DateTime](../../../system/datetime/). Valid formats include "yyyy-MM-ddTHH:mm:sszzzzzz" and its subsets. |

### Return Value

A [DateTime](../../../system/datetime/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** or an element of **formats** is [String::Empty](../../../system/string/empty/) or **s** does not contain a date and time that corresponds to any of the elements of **formats**. |


## XmlConvert::ToDateTime(const String&, XmlDateTimeSerializationMode) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) using the XmlDateTimeSerializationMode specified.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The [String](../../../system/string/) value to convert. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | One of the enumeration values that specify whether the date should be converted to local time or preserved as Coordinated Universal Time (UTC), if it is a UTC date. |

### Return Value

A [DateTime](../../../system/datetime/) equivalent of the [String](../../../system/string/).

### Exceptions

| Exception | Description |
| --- | --- |
| NullReferenceException | **s** is **nullptr**. |
| ArgumentNullException | **dateTimeOption** is **nullptr**. |
| FormatException | **s** is an empty string or is not in a valid format. |


## See Also

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)