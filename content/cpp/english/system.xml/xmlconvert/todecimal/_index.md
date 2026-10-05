---
title: ToDecimal()
second_title: Aspose.Slides for C++ API Reference
description: Converts the String to a Decimal equivalent.
type: docs
weight: 261
url: /system.xml/xmlconvert/todecimal/
---
## XmlConvert::ToDecimal(const String&) method


Converts the [String](../../../system/string/) to a [Decimal](../../../system/decimal/) equivalent.

```cpp
static Decimal System::Xml::XmlConvert::ToDecimal(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)& | The string to convert. |

### Return Value

A **[Decimal](../../../system/decimal/)** equivalent of the string.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **s** is **nullptr**. |
| FormatException | **s** is not in the correct format. |
| OverflowException | **s** represents a number less than [Decimal::MinValue](../../../system/decimal/minvalue/) or greater than [Decimal::MaxValue](../../../system/decimal/maxvalue/). |


## See Also

* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)