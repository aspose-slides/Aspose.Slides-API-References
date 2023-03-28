---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to converts the specified string to DateTimeOffset object.
type: docs
weight: 729
url: /cpp/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const [String](../../string/)\&, [DateTimeOffset](../)\&) method


Tries to converts the specified string to [DateTimeOffset](../) object.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/), [DateTimeOffset](../)\&) method


Tries to converts the specified string to [DateTimeOffset](../) object using the specified format provider and formatting style.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) that is equivalent to the **input**. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
