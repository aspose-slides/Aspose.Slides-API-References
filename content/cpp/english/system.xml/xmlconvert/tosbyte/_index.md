---
title: ToSByte()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a SByte equivalent.
type: docs
weight: 274
url: /system.xml/xmlconvert/tosbyte/
---
## XmlConvert::ToSByte(const String&) method


Converts the [String](../../../system/string/) to a [SByte](../../../system/sbyte/) equivalent.

```cpp
static int8_t System::Xml::XmlConvert::ToSByte(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

An **[SByte](../../../system/sbyte/)** equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [SByte::MinValue](../../../system/sbyte/minvalue/) or greater than [SByte::MaxValue](../../../system/sbyte/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)