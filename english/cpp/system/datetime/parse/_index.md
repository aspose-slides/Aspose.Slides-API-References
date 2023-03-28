---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string representation of a date and time value to the equivalent DateTime object.
type: docs
weight: 859
url: /cpp/system/datetime/parse/
---
## DateTime::Parse(const [String](../../string/)\&) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |

### Return Value

A new instance of [DateTime](../) class that represents the date and time value equivalent to that represented by the specified string.

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::Parse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using culture-specific format information.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The [IFormatProvider](../../iformatprovider/) object that provides culture-specific format information. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [DateTime](../) object. |

### Return Value

A new instance of [DateTime](../) class that represents the date and time value equivalent to that represented by the specified string.

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::Parse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::Parse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::Parse(const [String](../../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
