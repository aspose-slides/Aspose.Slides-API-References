---
title: ParseExact()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string representation of a date and time value to the equivalent DateTime object using the specified format and culture-specific format information. The format of the string representation must match the specified format exactly. Throws an exception if the conversion fails.
type: docs
weight: 872
url: /cpp/system/datetime/parseexact/
---
## DateTime::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using the specified format and culture-specific format information. The format of the string representation must match the specified format exactly. Throws an exception if the conversion fails.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |
| format | const [String](../../string/)\& | The string format. |
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
## DateTime::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using the specified formats, culture-specific format information and style. The format of the string representation must match one or more of the specified formats exactly. Throws an exception if the conversion fails.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | The array of string formats. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The [IFormatProvider](../../iformatprovider/) object that provides culture-specific format information. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [DateTime](../) object. |

### Return Value

A new instance of [DateTime](../) class that represents the date and time value equivalent to that represented by the specified string.

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/)) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## See Also

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
