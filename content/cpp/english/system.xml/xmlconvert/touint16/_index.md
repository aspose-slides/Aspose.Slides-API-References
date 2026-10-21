---
title: ToUInt16()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a UInt16 equivalent.
type: docs
weight: 339
url: /system.xml/xmlconvert/touint16/
---
## XmlConvert::ToUInt16(const String&) method


Converts the [String](../../../system/string/) to a [UInt16](../../../system/uint16/) equivalent.

```cpp
static uint16_t System::Xml::XmlConvert::ToUInt16(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

A [UInt16](../../../system/uint16/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [UInt16::MinValue](../../../system/uint16/minvalue/) or greater than [UInt16::MaxValue](../../../system/uint16/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)