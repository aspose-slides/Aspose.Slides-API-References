---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string representation of a date and time value to the equivalent DateTime object.
type: docs
weight: 885
url: /cpp/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) method


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

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


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

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)