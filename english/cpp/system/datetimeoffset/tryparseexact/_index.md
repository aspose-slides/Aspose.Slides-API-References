---
title: TryParseExact()
second_title: Aspose.Slides for C++ API Reference
description: Tries to converts the specified string to DateTimeOffset object using the specified formats, format provider and formatting style.
type: docs
weight: 742
url: /cpp/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tries to converts the specified string to [DateTimeOffset](../) object using the specified formats, format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrays of format strings. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tries to converts the specified string to [DateTimeOffset](../) object using the specified format, format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| format | const [String](../../string/)\& | Format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)