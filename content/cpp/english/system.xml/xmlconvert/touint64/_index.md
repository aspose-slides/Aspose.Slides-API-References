---
title: ToUInt64()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a UInt64 equivalent.
type: docs
weight: 365
url: /system.xml/xmlconvert/touint64/
---
## XmlConvert::ToUInt64(const String&) method


Converts the [String](../../../system/string/) to a [UInt64](../../../system/uint64/) equivalent.

```cpp
static uint64_t System::Xml::XmlConvert::ToUInt64(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

A [UInt64](../../../system/uint64/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [UInt64::MinValue](../../../system/uint64/minvalue/) or greater than [UInt64::MaxValue](../../../system/uint64/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)