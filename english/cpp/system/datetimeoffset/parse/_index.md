---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string to DateTimeOffset equivalent.
type: docs
weight: 703
url: /cpp/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const [String](../../string/)\&) method


Converts the specified string to [DateTimeOffset](../) equivalent.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |

### Return Value

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::Parse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method


Converts the specified string to [DateTimeOffset](../) object using the specified format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Date and time formatting styles. |

### Return Value

[DateTimeOffset](../) that is equivalent to the **input**.

## See Also

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
