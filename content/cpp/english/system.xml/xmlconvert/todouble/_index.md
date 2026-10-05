---
title: ToDouble()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a Double equivalent.
type: docs
weight: 391
url: /system.xml/xmlconvert/todouble/
---
## XmlConvert::ToDouble(String) method


Converts the [String](../../../system/string/) to a [Double](../../../system/double/) equivalent.

```cpp
static double System::Xml::XmlConvert::ToDouble(String s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | [String](../../../system/string/) | The string to convert. |

### Return Value

A [Double](../../../system/double/) equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [Double::MinValue](../../../system/double/minvalue/) or greater than [Double::MaxValue](../../../system/double/maxvalue/). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)