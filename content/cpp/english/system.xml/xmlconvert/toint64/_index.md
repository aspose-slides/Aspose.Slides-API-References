---
title: ToInt64()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a Int64 equivalent.
type: docs
weight: 313
url: /system.xml/xmlconvert/toint64/
---
## XmlConvert::ToInt64(const String&) method


Converts the [String](../../../system/string/) to a [Int64](../../../system/int64/) equivalent.

```cpp
static int64_t System::Xml::XmlConvert::ToInt64(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

An [Int64](../../../system/int64/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [Int64::MinValue](../../../system/int64/minvalue/) or greater than [Int64::MaxValue](../../../system/int64/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)