---
title: ToInt16()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a Int16 equivalent.
type: docs
weight: 287
url: /system.xml/xmlconvert/toint16/
---
## XmlConvert::ToInt16(const String&) method


Converts the [String](../../../system/string/) to a [Int16](../../../system/int16/) equivalent.

```cpp
static int16_t System::Xml::XmlConvert::ToInt16(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

An [Int16](../../../system/int16/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [Int16::MinValue](../../../system/int16/minvalue/) or greater than [Int16::MaxValue](../../../system/int16/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)