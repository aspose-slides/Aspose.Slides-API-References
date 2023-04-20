---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts string to equivalent TimeSpan object and returns result of conversion.
type: docs
weight: 560
url: /cpp/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) method


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

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


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

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)