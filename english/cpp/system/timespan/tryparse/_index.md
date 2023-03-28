---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts string to equivalent TimeSpan object and returns result of conversion.
type: docs
weight: 560
url: /cpp/system/timespan/tryparse/
---
## TimeSpan::TryParse(const [String](../../string/)\&, [TimeSpan](../)\&) method


Converts string to equivalent [TimeSpan](../) object and returns result of conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| result | [TimeSpan](../)\& | Time interval that corresponds to string. |

### Return Value

True if string was converted successfully; otherwise, false.

## See Also

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, [TimeSpan](../)\&) method


Converts string to equivalent [TimeSpan](../) object using the specified format provider and returns result of conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| result | [TimeSpan](../)\& | Time interval that corresponds to string. |

### Return Value

True if string was converted successfully; otherwise, false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, [TimeSpan](../)\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::TryParse(const [String](../../string/)\&, const [SharedPtr](../../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](../)\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TimeSpan::TryParse(const [String](../../string/)\&, std::nullptr_t, [TimeSpan](../)\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
