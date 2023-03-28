---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string representation of a date and time value to the equivalent DateTime object.
type: docs
weight: 885
url: /cpp/system/datetime/tryparse/
---
## DateTime::TryParse(const [String](../../string/)\&, [DateTime](../)\&) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |
| result | [DateTime](../)\& | The output argument that, if the conversion succeeds, contains the result of conversion. |

### Return Value

True if conversion succeeds, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/), [DateTime](../)\&) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using the specified culture-specific format information and style.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a date and time value to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The [IFormatProvider](../../iformatprovider/) object that provides culture-specific format information. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [DateTime](../) object. |
| result | [DateTime](../)\& | The output argument that, if the conversion succeeds, contains the result of conversion. |

### Return Value

True if conversion succeeds, otherwise - false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/), [DateTime](../)\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/), [DateTime](../)\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::TryParse(const [String](../../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/), [DateTime](../)\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
