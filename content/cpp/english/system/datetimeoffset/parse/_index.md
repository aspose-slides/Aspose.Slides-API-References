---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string to DateTimeOffset equivalent.
type: docs
weight: 703
url: /system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) method


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

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


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

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)