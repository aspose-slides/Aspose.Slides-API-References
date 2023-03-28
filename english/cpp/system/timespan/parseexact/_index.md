---
title: ParseExact()
second_title: Aspose.Slides for C++ API Reference
description: Converts string to equivalent TimeSpan object using the specified formats, format provider and styles.
type: docs
weight: 547
url: /cpp/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method


Converts string to equivalent [TimeSpan](../) object using the specified formats, format provider and styles.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) of format strings. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Defines elements that may be present in input string. |

### Return Value

Time interval that corresponds to string.

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method


Converts string to equivalent [TimeSpan](../) object using the specified format, format provider and styles.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| format | const [String](../../string/)\& | Standard or custom format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Defines elements that may be present in input string. |

### Return Value

Time interval that corresponds to string.

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::ParseExact(const [String](../../string/)\&, const [String](../../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/)) method




```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## See Also

* Class [TimeSpan](../)
* Class [String](../../string/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
