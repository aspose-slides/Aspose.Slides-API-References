---
title: ParseExact()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string to DateTimeOffset object using the specified format, format provider and formatting style.
type: docs
weight: 716
url: /system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Converts the specified string to [DateTimeOffset](../) object using the specified format, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| format | const [String](../../string/)\& | Format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |

### Return Value

[DateTimeOffset](../) that is equivalent to the **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Converts the specified string to [DateTimeOffset](../) object using the specified formats, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) of format strings. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |

### Return Value

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)