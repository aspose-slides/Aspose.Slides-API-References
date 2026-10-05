---
title: ToInt32()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a Int32 equivalent.
type: docs
weight: 300
url: /system.xml/xmlconvert/toint32/
---
## XmlConvert::ToInt32(const String&) method


Converts the [String](../../../system/string/) to a [Int32](../../../system/int32/) equivalent.

```cpp
static int32_t System::Xml::XmlConvert::ToInt32(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

An [Int32](../../../system/int32/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [Int32::MinValue](../../../system/int32/minvalue/) or greater than [Int32::MaxValue](../../../system/int32/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)